# Banda clasificadora por altura — Control con PLC

Sistema de clasificación automática de cajas por altura,
programado en lógica escalera con CODESYS.

## ¿Qué hace?

EL sistema ayuda a optimizar la clasificación de caja en una linea de producción, asegurándose que no midan menos de 59 centímetros ni mas de 61 centímetros, para asegurar un control de calidad. 

## Herramientas

CODESYS V3.5, lenguaje escalera (LD), simulación en CODESYS Control Win V3

## Documentación

La descripción funcional completa está en descripcion_funcional.md

## Hallazgos

Existe un defecto de seguridad, ya que si se activa el paro de emergencia mientras los pistones están accionados para sacar a una pieza defectuosa de la linea de producción, estos no se detienen hasta cumplir su ciclo. Se tiene contemplado este defecto para una corrección futura.
