# Hello Datbricks

## Tutorial rápido: Integrando GitHub ao Databricks

1. **Crie um token de acesso no GitHub**
   - Vá em *Settings* > *Developer settings* > *Personal access tokens*.
   - Clique em *Generate new token*.
   - Selecione escopo `repo` e copie o token gerado.

2. **Configure o token no Databricks**
   - No Databricks, acesse *User Settings* > *Linked accounts*.
   - Cole o token do GitHub.

3. **Clone o repositório no Databricks**
   - No menu lateral, clique em *Repos* > *Add Repo*.
   - Insira a URL do seu repositório GitHub e clique em *Clone*.

4. **Edite e sincronize seus notebooks**
   - Abra o repositório clonado.
   - Edite arquivos e notebooks normalmente.
   - Use *Git* > *Commit & Push* para sincronizar alterações com o GitHub.

Pronto! Seu Databricks está integrado ao GitHub.