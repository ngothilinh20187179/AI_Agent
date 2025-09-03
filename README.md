# AI Agent simple for beginners

# Course Setup
- Python 3.12+
- Install requirements
    pip install -r requirements.txt
- Create Your .env File 
- Run .env file

Set Up for Samples using GitHub Models
- Retrieve Your GitHub Personal Access Token (PAT)
    + Generate new token https://github.com/settings/personal-access-tokens
    + Token name ex: ms_ai_agents_token
    + Expiration ex: 30 days
    + Repository access ex: Only select repository
    + Set Permissions
- Copy new token and add to .env file (GITHUB_TOKEN="...")

Set Up for Samples using Azure AI Foundry and Azure AI Agent Service
- Retrieve Your Azure Project Endpoint
    + Create Account Azure: https://portal.azure.com/
    + Create Azure AI Foundry: https://ai.azure.com/
- Copy and add to .env file (AZURE_AI_PROJECT_ENDPOINT="Azure AI Foundry Project endpoint")
- Add to .env file (Used For Running Samples Using Azure OpenAI Service + Azure Search )
    + AZURE_SUBSCRIPTION_ID
    + AZURE_AI_PROJECT_NAME
    + ...

### .env
- GLOBAL_LLM_SERVICE=AzureOpenAI
- GITHUB_TOKEN="..." 

- AZURE_SUBSCRIPTION_ID="..."
- AZURE_TENANT_ID="..."
- AZURE_CLIENT_ID="..."
- AZURE_CLIENT_SECRET="..."

- AZURE_AI_RESOURCE_GROUP=rg-ngothilinhau12915-ai-fo-pj
- AZURE_AI_PROJECT_NAME=ngothilinhau12915-ai-fo-pj
- AZURE_AI_PROJECT_ENDPOINT=https://ngothilinhau12915-ai-fo-resource.services.ai.azure.com/api/projects/ngothilinhau12915-ai-fo-pj
- AZURE_SERVICE_ENDPOINT=https://ngothilinhau12915-ai-fo-resource.cognitiveservices.azure.com
- AZURE_OPENAI_ENDPOINT=https://ngothilinhau12915-ai-fo-resource.openai.azure.com
- AZURE_OPENAI_DEPLOYMENT_NAME=gpt-4o-mini
- AZURE_OPENAI_MODEL=gpt-4o-mini
- AZURE_OPENAI_API_VERSION=2025-01-01-preview

- AZURE_OPENAI_API_KEY="..."
- AZURE_OPENAI_EMBEDDING_DEPLOYMENT_NAME="..."
- AZURE_OPENAI_CHAT_DEPLOYMENT_NAME="..."
- AZURE_OPENAI_SERVICE="..."
- AZURE_SEARCH_SERVICE_ENDPOINT = "..."
- AZURE_SEARCH_API_KEY = "..."
- AZURE_AI_AGENT_MODEL_DEPLOYMENT_NAME="..."
- AZURE_AI_AGENT_PROJECT_CONNECTION_STRING="..."
- OPENAI_API_KEY="..."

### Ref
https://github.com/microsoft/ai-agents-for-beginners/tree/main/00-course-setup
