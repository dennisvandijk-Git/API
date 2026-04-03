# ⚡ Cloud Resume Challenge – Backend API

Deze repository bevat de backend API voor mijn Cloud Resume Challenge project.

De API is gebouwd met serverless technologieën in Azure en is verantwoordelijk voor het bijhouden en teruggeven van de bezoekerteller op mijn website.

🔗 Frontend: https://www.dvandijk.com  

---

## 📌 Over dit project

Deze backend stelt een HTTP API beschikbaar die:

- Verzoeken ontvangt vanuit de frontend  
- De bezoekerteller verhoogt  
- De actuele waarde terugstuurt  

De oplossing is opgezet volgens een serverless architectuur met Azure Functions en een CosmosDB Table.

---

## 🧠 Functionaliteit

- 📊 Verhoogt de visitor count bij elke aanvraag  
- 🔄 Retourneert de nieuwe waarde als JSON  
- 🌐 Bereikbaar via een HTTP endpoint  
- ⚡ Draait volledig serverless  

---

## 🏗️ Architectuur

- ⚡ Azure Functions — HTTP-triggered API  
- 🗄️ Azure Cosmos DB — opslag van de visitor count  
- 🌐 Cloudflare — DNS, CDN en routing  
- 💻 Frontend (aparte repository) die de API aanroept  

---

## 🔌 API Endpoint

Voorbeeld request:

```http
GET https://visitor-counter-api-http-trigger.azurewebsites.net/api/visitor_counter
