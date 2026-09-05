# Requirements

1. `github-user`
2. `github-token`
3. `db-connection-url`


## Definitions

- *Inputs*:
    - `github-user`:
      - **description**: 'Github Username used as reference to get all it starred repositories'
      - **required**: true
      - **default**: ''
    - `github-token`:
      - **description**: 'Acces Token for the github API'
      - **required**: true
      - **default**: ''
    - `db-connection-url`:
      - **description**: 'Postgres connection string (e.g. `postgresql://postgres.[PROJECT_ID]:[PASSWORD]@aws-0-us-west-2.pooler.supabase.com:5432/postgres`)
      - **required**: true
      - **default**: ''
