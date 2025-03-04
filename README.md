<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watson Assistant Chat</title>
</head>
<body>
    <h2>Testing Watson Assistant Chatbot</h2>
    <script>
        window.watsonAssistantChatOptions = {
            integrationID: "529b286a-997c-4443-b057-8b49002460e7", // The ID of this integration.
            region: "eu-gb", // The region your integration is hosted in.
            serviceInstanceID: "6bb86cbe-f17d-4e03-9f5e-7460b3bd0b10", // The ID of your service instance.
            onLoad: async (instance) => { await instance.render(); }
        };
        setTimeout(function(){
            const t=document.createElement('script');
            t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/latest/WatsonAssistantChatEntry.js";
            document.head.appendChild(t);
        }, 1000);
    </script>
</body>
</html>
