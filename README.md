
- Consultas (Queries):  
  Permiten obtener información sobre usuarios y organizaciones que pueden ser patrocinados. Incluyen filtros como ecosistema de dependencias, paginación (first, last, after, before) y ordenamiento.

- Mutaciones (Mutations):  
  - cancelSponsorship: Cancela un patrocinio activo.  
  - createSponsorship: Inicia o reactiva un patrocinio.  
  - createSponsorships: Permite patrocinar múltiples usuarios/organizaciones a la vez.  
  - createSponsorsListing: Crea un perfil para que otros puedan patrocinarte.  
  - createSponsorsTier: Define un nuevo nivel de pago.  
  - publishSponsorsTier: Publica un nivel de patrocinio en borrador.  
  - retireSponsorsTier: Retira un nivel publicado.  
  - updatePatreonSponsorability: Desactiva la opción de recibir patrocinios vía Patreon.  
  - updateSponsorshipPreferences: Cambia visibilidad y preferencias de notificaciones.

- Objetos y conexiones:  
  - SponsorAndLifetimeValue: Relaciona un patrocinador con el monto total aportado.  
  - SponsorConnection, SponsorEdge: Estructuras para manejar listas y paginación.  
  - SponsorsTier: Define niveles de patrocinio con información administrativa.  
  - SponsorsListing: Perfil público de patrocinadores.

- Enums y entradas:  
  Incluyen campos de orden, tipos de acciones de actividad, periodos, privacidad, fuentes de pago y entradas para crear/retirar niveles o listados.

✨ En resumen
La documentación describe cómo usar el GraphQL API de GitHub Sponsors para consultar, crear, modificar o cancelar patrocinios, así como administrar perfiles y niveles de patrocinio. Es una referencia técnica para desarrolladores que integran o gestionan patrocinios dentro de GitHub.


