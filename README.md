# Consulta CPE - OpenAPI

Especificación OpenAPI de [Consulta Integrada de Comprobante de Pago](https://cdn.www.gob.pe/uploads/document/file/536289/Manual_de_Consulta_Integrada_de_Validez_de_CdP_por_Servicio_WEB.pdf) - SUNAT

<p>
  <img height="100px" src="https://static1.smartbear.co/swagger/media/assets/images/sw_ov_intro_band1_icon1.svg" alt="OpenAPI"/>
</p>

## Uso
Puedes generar sdk para diferentes lenguajes de programación, utilizando la herramienta online 
de swagger.

- [OpenAPI 2.0](https://editor.swagger.io/?url=https://raw.githubusercontent.com/thegreenter/consulta-cpe-openapi/master/swagger.yaml)
- [OpenAPI 3.0](https://editor.swagger.io/?url=https://raw.githubusercontent.com/thegreenter/consulta-cpe-openapi/master/openapi.yaml)


![Swagger gen client](https://raw.githubusercontent.com/thegreenter/consulta-cpe-openapi/master/resources/swagger-gen-client.png)

Necesitarás las credenciales para acceder al API, puedes seguir [la guía oficial](https://orientacion.sunat.gob.pe/images/imagenes/contenido/comprobantes/Manual-de-Consulta-Integrada-de-Comprobante-de-Pago-por-ServicioWEB.pdf).
- `client_id`
- `client_secret`

Existen 2 rutas en el API
- Obtener el Token de acceso. (Host: `https://api-seguridad.sunat.gob.pe/v1`)
- Realizar la consulta de comprobante. (Host: `https://api.sunat.gob.pe/v1`)
