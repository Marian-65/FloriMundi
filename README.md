# FloraMundi
Práctica de examen usando FloraMundi como ejemplo

JERARQUIA
 - DIRECCION

   -- CONFIDENCIAL
   
   -- LIBRE
 - CALIDAD
 - OPERATIVA
   
   -- PRODUCCION

   -- LOGISTICA
 - COMERCIAL_MARKETING
 - LEGAL

El criterio de jerarquía ha sido mediante Secciones de la lógica de negocio y un segundo criterio sobre los permisos del documento.



POSIBLES ETIQUETAS

- SEDE: espana, paises_bajos, colombia, kenia
- PRODUCTO: lirio, rosa, clavel, orquidea
- TIPO_DOCUMENTO: ficha_tecnica, certificado, contrato, guia_tecnica, pedido, factura
- TEMPORADA: verano, navidad, invierno
- ESTADO: borrador, en_revision, en_proceso, archivado, publicado, rechazado


PLANTILLA METADATOS
---
codigo: FM_ES_ROS_2026_001
titulo: Ficha tecnica Rosa del Desierto
sede:  espana
estado: Aprobado
version: 1.0
responsable: Juan Gonzalez
fecha_creacion: 01/05/2026
fecha_revision: 02/05/2026
palabras_clave: [rosa, flor, SemillasDeOro, sustrato_tipoC]
---

NOMENCLATURA
TIPO DE DOCUMENTO: GUIAS TECNICAS DE FLORES
FM_ESROS_2026_001.PDF
He usado la inicial de la empresa
La sede, el código de producto ROS=Rosa
año y el nº de versión.

FM-COLIR_2025_034.PDF

TIPO DE DOCUMENTO: PEDIDOS
PEDFM_ES_01052026_009878_0534.PDF
PED pedido + FM Floramundi + Sede + Fecha + nºCliente + nºpedido

PEDFM_NL_05052026_15763_12.PDF

FLUJO DE TRABAJO
- Issue para pedir documento o modificacion --> tecnico
- Crea una rama para el documento segun tipo --> nuevas-rosas
- Edita el documento por parte del semillero
- Abre un pull Request (peticion de aprobacion)
- El verificador/responsable aprueba y hace MERGE
- Le coloca la etiqueta de PUBLICADO y lo coloca en la carpeta DOCUMENTOS_PUBLICOS o la WEB... (ejemplo)

Estado inicial del documento
que actor tiene que hacer
qué tiene que hacer (tarea, condiciones, plazo)
y cuál sería el estado siguiente

Contrato 
--- Borrador Tecnico de RRHH -- Redactarlo -- 
EnRevision -- Responsable RRHH - Revisar y validar --Aprobado
Aprobado --CEO --Firmar y sellar -- Publico

Estados del Documento =  CICLO DE VIDA DEL DOCUMENTO
BORRADOR
ENREVISION
APROBADO
PUBLICO
ARCHIVADO
ELIMINADO (no llegaria a ponerse)


                   DIRECTOR         RESPONSABLE_AREA          EDITOR            EXTERNO

PEDIDO                VER                VER/EDITAR            CREAR              NADA

GUIA_TECNICA          VER                   VER             CREAR/EDITAR          VER

CONTRATO_LABORAL     EDITAR                 VER                 NO                 NO
                    (Aprobar)
