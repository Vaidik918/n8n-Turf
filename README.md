# n8n-Turf
Turf Booking Automation
The awful process of booking slots at a turf is broken and slow with a loop stuck is messaging/calling, waiting, trying to fix timings, etx.

The Solution built by Vaidik, is a 24/7 WhatsApp booking assistant that confirms slots, handles payments and offers smart alternatives.
<img width="1328" height="784" alt="image" src="https://github.com/user-attachments/assets/1004cd3f-ba70-4ab4-a3ee-ace43b4bc8ad" />

Uses Supabase as backend enabling lightning quick updates and real time slot allotments.
<img width="836" height="702" alt="image" src="https://github.com/user-attachments/assets/92892548-d609-43e9-9835-aa989cb4c539" />

Gemini 2.5 model is used to get the user's intent ( and acts as smart assistant to clarify typos and mistakes), which is then used in switch nodes, which routes the flow along the respective paths.
Twilio for WhatsApp messaging API.

<img width="650" height="709" alt="image" src="https://github.com/user-attachments/assets/71977ca6-c0cc-41af-a693-6c92807f4437" />

And Razorpay for payments

A brief description of the Worfflow :
1. The User sends a WhatsApp message to trigger a Web Hook.
2. The System shows the options and then later identifies the turf the user selected.
3. The System keeps track on information and asks in case the user misses details.
4. The System confirms the slot availability and the Users feedback, it sends payment link.
5. The slot gets booked in the backend, the users gets a confirmation message on WhatsApp and the owner gets a confirmation email.


In Development...
