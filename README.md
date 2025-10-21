## Overview
CustomerSupportBot is a customer support chatbot built using Dialogflow.  
It can handle queries related to:

- Greeting users  
- Checking Order Status  
- Return / Refund requests  
- Cancel Orders  
- Small talk (Hi, How are you, Thanks, Bye)

The bot is branded as **Future Intern Helpdesk** and supports multi-turn conversations using **contexts**.

---

## Features
- Multi-turn conversation with contexts (`awaiting_order_id`, `awaiting_return_id`, `awaiting_cancel_id`)  
- Formal responses with professional branding  
- Fallback responses for unrecognized input  
- Small talk for a more human-like interaction  
- Optional integration with Web Demo or Telegram  

---

## Folder Structure
CustomerSupportBot/
│
├── dialogflow-agent/ # Exported Dialogflow agent ZIP
├── docs/ # Optional demo conversation flows
├── README.md # Project overview
└── LICENSE # MIT or other license

yaml
Copy code

---

## How to Use
1. Import the agent ZIP in Dialogflow:  
   - Go to **Settings ⚙️ → Export and Import → Restore from ZIP**  
   - Select `CustomerSupportBot.zip`  
2. Test the chatbot in the **Try it now** panel.  
3. Optional: Integrate with Web Demo or Telegram via **Integrations**.  

---

## Conversation Flow Example
1. **User:** Hi  
   **Bot:** Hello! Welcome to Future Intern Helpdesk. How may I assist you today?  

2. **User:** Where is my order?  
   **Bot:** Sure! Please provide your order ID so I can check its status.  

3. **User:** 12345  
   **Bot:** Thanks! Checking order #12345… Your order is currently out for delivery.  

4. **User:** I want a refund  
   **Bot:** Please provide your order ID to initiate the refund.  

5. **User:** 55421  
   **Bot:** Got it! Your refund request for order #55421 has been initiated ✅
