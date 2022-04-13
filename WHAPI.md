# Wiki Helper API (WHAPI)
  
  - Pure Wiki Server Side API
  
## RESTful CRUD+Meta
    - CREATE PAGE ... `PUT /path/to/endpoint`
    - READ PAGE ... `GET /path/to/endpoint?type=[html|pdf|md]`
    - UPDATE ... `PUT /path/to/endpoint`
    - DELETE ... `DELETE /path/to/endpoint`
    - Manage Meta Data, Extension ... `POST /request/path/name` with JSON.
      - Tag, Editor, References... and?
      - Tag: MultiLanguage
    
  - Managed/Insipred Git(One Server One Repository, repository-name: FQDN?)
    - Req: `PUT X-Update-Type: Draft` --> `checkout -b [username]` ---> Save Draft at `[username]` branch.
    - Req: `PUT X-Update-Type: Commit` ---> Save Docs with Commit Mesg at `[username]` branch.
    - Req: `POST /version-control/merge` ---> merge to another branch(e.g. public, main, community_name)
    - Req: `POST /version-control/clone` ---> clone to my server.
    - Req: `POST /version-control/request-pull` ---> req pull.
    - Req: `POST /version-control/pull` ---> pull to upper stream.
    - Req: `POST /version-control/push` ---> push from down stream.
    - Req: `POST /search` with keyword and page ---> return result JSON.
    - Req: `POST /info/latest-updates`, `POST /
  - Linking Other WHAPI Server
    - GET Search Index Difference Data `POST /public-data/indexes`
    - GET Another Server Information via DHT?, RoutingTable?:  `POST /public-data/servers`
      - IRC/Matrix Integration: Discussion between servers.

## Extensions

### References Integration

- Cite? Paraphrase Quote?, Direct Quote?, bibliography?, reference?

### Other

- Similar Document Detection
- Review(Comment)
- 


# WHAPI Frontend Implemantaion
  
  - Search Communicaton
  - Dynamic Applied Style Sheet.(dark/light, Page)
  - Editor
  - ServerSide Rendering
    - When access as `GET /path/to/endpoint` to `docs.example.com`, srv commnucate to `api.example.com` and rendering with utlitys(e.g. Navbar).
