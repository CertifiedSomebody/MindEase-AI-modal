# MindEase Chatbot

MindEase is a mental wellness companion chatbot built using **IBM Watson Assistant**.  
This project includes a simple HTML page with dark/light theme toggle and an embedded Watson Assistant integration.

---

## 🚀 Features
- Dark/Light mode toggle 🌗
- Responsive design for mobile and desktop
- Watson Assistant Web Chat integration
- Sample prompts for the user to try

---

---

## 🔧 Watson Assistant Integration

The chatbot is powered by an IBM Watson Assistant instance.

### Integration Details:
- **Integration ID:** `e62c5a02-e425-4564-8890-43fcf689765d`
- **Service Instance ID:** `1e6edbd4-4510-41e5-83f0-cc3230ecf800`
- **Region:** `au-syd`

These values are already set in the html file:
```javascript
window.watsonAssistantChatOptions = {
  integrationID: "e62c5a02-e425-4564-8890-43fcf689765d",
  region: "au-syd",
  serviceInstanceID: "1e6edbd4-4510-41e5-83f0-cc3230ecf800",
  onLoad: async (instance) => { await instance.render(); }
};
