```mermaid
flowchart LR
  SampleApp_Web["SampleApp:Web"] -->|"HTTPS"| SampleApp_API["SampleApp:API"]
  SampleApp_API["SampleApp:API"] -->|"SQL"| SampleApp_DB["SampleApp:DB"]

