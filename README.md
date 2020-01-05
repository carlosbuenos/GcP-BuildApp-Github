# Gke-App-Terraform
Script que ensina basicamente como implantar um aplicativo com Terraform no GKE

# Fonte dos primeiros passos.
   https://cloud.google.com/solutions/managing-infrastructure-as-code?hl=pt-br
   
# Primeiros passos.
&nbsp;&nbsp;No Cloud Shell, consiga o código do projeto que você acabou de selecionar.<br/>
&nbsp;&nbsp;&nbsp; - $ gcloud config get-value project<br/>
&nbsp;&nbsp;Se este comando não retornar o código, configure o Cloud Shell para usar seu projeto. Substitua PROJECT_ID pelo código do seu projeto.<br/>
&nbsp;&nbsp;&nbsp; - $ gcloud config set project PROJECT_ID


# Ative as APIs necessárias 
&nbsp;&nbsp;Cloud Build<br/>
&nbsp;&nbsp;Cloud Storage<br/>
&nbsp;&nbsp;Compute Engine<br/>

Execute o comando abaixo para executar a ativação caso não estejam ativados: Isto pode demorar alguns minutos. <br/>
&nbsp;&nbsp;&nbsp; - $ gcloud services enable cloudbuild.googleapis.com compute.googleapis.com

# Se você nunca usou o Git no Cloud Shell, configure-o com seu nome e endereço de e-mail:
&nbsp;&nbsp;&nbsp;git config --global user.email "your-email-address"<br/>
&nbsp;&nbsp;&nbsp;git config --global user.name "your-name"<br/>
