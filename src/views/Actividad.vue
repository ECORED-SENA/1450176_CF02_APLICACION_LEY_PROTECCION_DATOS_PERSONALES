<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      // Para cuestionario usar: <ActividadController :cuestionario="cuestionario"/>
      // Para parrafo usar: <ActividadController :parrafo="parrafo"/>
      #Actividad                
      <ActividadController :cuestionario="cuestionario"/>

</template>

<script>
import ActividadController from '@ecored-sena/boulder-kit/plugin/components/actividad/ActividadController.vue'

export default {
  name: 'ActividadDidactica',
  components: {
    ActividadController,
  },
  data: () => ({
    cuestionario: {
      tema: 'Buenas Prácticas para la Protección de Datos Personales',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo:</b> identificar los conceptos clave relacionados con el diagnóstico, tratamiento responsable, protección, control y gestión de riesgos de los datos personales.',
      barajarPreguntas: false,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es el propósito principal del diagnóstico organizacional del tratamiento de datos personales?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Reconocer cómo se recolecta, almacena, usa, comparte y conserva la información.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Establecer únicamente los costos tecnológicos destinados a almacenar la información.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Determinar exclusivamente las funciones laborales asignadas a cada área organizacional.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Identificar solamente los documentos físicos existentes dentro de la organización.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué característica debe tener la finalidad del tratamiento de datos personales?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Ser general, flexible y aplicable a cualquier actividad futura prevista.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Ser clara, específica y comprensible para el titular de los datos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Ser reservada, interna y conocida solamente por el personal administrativo autorizado.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Ser amplia, permanente y modificable según las necesidades comerciales posteriores.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué tipo de datos requiere mayor reserva por pertenecer al ámbito personal del titular?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Datos públicos disponibles en registros y documentos oficiales de libre consulta.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Datos semiprivados relacionados con información financiera y decisiones de carácter comercial.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Datos privados relacionados con información personal, laboral, familiar o contractual.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Datos institucionales relacionados con procesos administrativos y actividades generales de gestión.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál de las siguientes acciones corresponde a una medida reforzada para proteger datos sensibles?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Permitir su consulta general cuando faciliten las actividades administrativas de la organización.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Conservarlos permanentemente aunque hayan dejado de ser necesarios para el proceso correspondiente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Compartirlos entre todas las áreas para facilitar la gestión interna de la organización.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Restringir su acceso únicamente al personal debidamente autorizado para realizar el tratamiento.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Qué debe solicitar un formulario adecuado para la recolección de datos personales?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Únicamente los datos necesarios para cumplir con una finalidad previamente definida.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Todos los datos disponibles que puedan resultar útiles para actividades organizacionales futuras.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Información adicional del titular aunque no guarde relación directa con el trámite.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'La mayor cantidad posible de información para completar posteriormente diferentes bases organizacionales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué permite demostrar una autorización física o digital conservada adecuadamente?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Que todos los datos recolectados pueden utilizarse libremente para cualquier actividad organizacional.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Que el titular autorizó el tratamiento de sus datos para una finalidad determinada.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Que la organización puede conservar indefinidamente toda la información proporcionada por el titular.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Que cualquier trabajador puede consultar los datos recolectados durante sus actividades laborales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Qué situación constituye un hallazgo básico durante el diagnóstico del tratamiento de datos?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La existencia de responsables claramente definidos para administrar cada base de datos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'La actualización periódica de las políticas internas relacionadas con el tratamiento de información.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La existencia de bases de datos antiguas que permanecen almacenadas sin depuración.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'La aplicación de controles adecuados para restringir el acceso a información personal reservada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Cuál es el propósito principal de los controles administrativos para proteger datos personales?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Proteger exclusivamente los dispositivos tecnológicos donde permanecen almacenados los datos personales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Restringir físicamente el ingreso de trabajadores a todas las instalaciones de la organización.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Sustituir las políticas internas mediante herramientas automáticas de almacenamiento y recuperación documental.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Establecer reglas, responsabilidades, procedimientos y formación para manejar adecuadamente los datos personales.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué función cumplen las políticas internas de tratamiento de datos personales?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Orientar cómo recolectar, usar, almacenar, proteger y eliminar los datos dentro de la organización.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Autorizar automáticamente cualquier tratamiento realizado por las diferentes áreas de la organización.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Permitir que cada trabajador establezca individualmente las condiciones para utilizar información personal.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Reemplazar los controles técnicos y físicos implementados para proteger adecuadamente la información personal.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es una consecuencia de no definir claramente los roles y responsabilidades?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Mayor control sobre las personas que pueden consultar información dentro de cada proceso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Mayor riesgo de accesos indebidos, pérdida de soportes y uso de datos no autorizado.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Mayor precisión para determinar quién debe responder oportunamente las solicitudes de los titulares.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Mayor capacidad para identificar las personas responsables de actualizar las bases de datos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            '¿Qué compromiso corresponde a un acuerdo de confidencialidad?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Compartir información con otros trabajadores siempre que pertenezcan a la misma organización.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Guardar copias personales de documentos cuando puedan ser útiles para actividades laborales posteriores.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Utilizar la información únicamente para los fines autorizados relacionados con las funciones asignadas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Mantener disponibles los datos después de finalizar funciones para facilitar posibles consultas futuras.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            '¿Cuál es una buena práctica relacionada con las contraseñas y la autenticación?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Utilizar una misma contraseña robusta para facilitar el acceso a todos los sistemas disponibles.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Compartir las claves con compañeros del área para asegurar la continuidad de las actividades.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Mantener activos los accesos anteriores para facilitar posibles consultas de trabajadores retirados.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Activar el doble factor de autenticación cuando sea posible para fortalecer el control.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto: '¿Cuál es la finalidad principal de las copias de seguridad?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Recuperar información ante pérdidas, daños, eliminaciones accidentales o incidentes de seguridad.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Facilitar el acceso general de los trabajadores a todos los archivos almacenados institucionalmente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Conservar indefinidamente información personal aunque haya desaparecido la finalidad que justificaba mantenerla.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Duplicar todas las bases personales en dispositivos particulares para garantizar disponibilidad inmediata.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: '¿En qué consiste el control de accesos por perfiles?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Permitir que todos los trabajadores consulten información mientras utilicen credenciales personales correctamente asignadas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Permitir que cada persona acceda únicamente a la información necesaria para sus funciones.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Asignar permisos generales a cada área para evitar solicitudes frecuentes de autorización institucional.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Autorizar automáticamente las descargas de información cuando provengan de equipos registrados institucionalmente.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            '¿Qué característica distingue principalmente a los controles físicos de protección?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Definen las finalidades autorizadas para recolectar y utilizar los datos personales de titulares.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Establecen los procedimientos internos que deben aplicar las diferentes áreas para gestionar información.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Protegen documentos, equipos, archivos, soportes y espacios donde permanece almacenada información personal.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Determinan las configuraciones digitales utilizadas para autenticar usuarios y cifrar las bases personales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 16,
          texto:
            '¿Qué derecho puede ejercer un titular respecto de sus datos personales?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Solicitar acceso permanente a todas las bases de datos administradas por la organización responsable.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Modificar directamente cualquier registro institucional sin presentar previamente una solicitud ante el responsable.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Exigir que toda información personal sea eliminada inmediatamente sin considerar las condiciones aplicables.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Solicitar la actualización, rectificación o supresión de sus datos cuando corresponda.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 17,
          texto:
            '¿Cuál de las siguientes situaciones puede considerarse un incidente de seguridad?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Enviar información personal por equivocación a un destinatario que no estaba autorizado.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Actualizar correctamente una base después de recibir una solicitud presentada por el titular.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Restringir el acceso a documentos personales únicamente a trabajadores previamente autorizados para consultarlos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Eliminar información que dejó de ser necesaria mediante un procedimiento institucional previamente establecido.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 18,
          texto:
            '¿Qué debe hacer una organización cuando identifica un incidente relacionado con datos personales?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Eliminar inmediatamente cualquier evidencia disponible para impedir la divulgación posterior del incidente ocurrido.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Registrar lo ocurrido, evaluar su impacto y aplicar las acciones correctivas y preventivas necesarias.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Esperar nuevos incidentes similares antes de modificar los procedimientos y controles internos correspondientes.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Comunicar públicamente toda la información afectada para garantizar transparencia frente a cualquier persona interesada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 19,
          texto:
            '¿Qué situación puede generar un riesgo legal relacionado con el tratamiento de datos personales?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Mantener canales definidos para atender las consultas y solicitudes presentadas por los titulares.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Revisar periódicamente las políticas internas cuando cambien procesos, finalidades o formas de almacenamiento.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Utilizar datos personales para finalidades diferentes de aquellas previamente informadas y autorizadas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Aplicar medidas reforzadas de seguridad cuando se manejan datos sensibles dentro de la organización.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 20,
          texto:
            '¿Qué busca la mejora continua en la protección de datos personales?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Mantener permanentemente los mismos controles para garantizar uniformidad en todos los procesos organizacionales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Actualizar exclusivamente los sistemas tecnológicos cuando ocurra un incidente grave relacionado con información personal.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Conservar las políticas originales aunque cambien las finalidades, plataformas y responsables del tratamiento.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Revisar periódicamente los controles, identificar cambios y aplicar ajustes para fortalecer la protección de los datos personales.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
