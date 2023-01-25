# AirborneDiseaseAssistant
This system presents a way to address the problem of neglecting safety measures during an airborne disease outbreak, which can lead to a pandemic by implementing a two-model system, one passive and one active.
The passive model consists of a face mask detection system using the Haar Cascade
Frontal face classifier and OpenCV, along with a social distancing model using simple Euclidean
distance of bonding boxes to check social distance violations and flag the user whenever pedestrians
are dangerously close and violating social distancing. The active model includes an interactive chatbot
built using Telegram, collecting the user information and checking whether they need to request
assistance or not. For future scalability, availability, and cost-effectiveness of this project, cloud
services like Microsoft Azure/ Amazon AWS can be implemented.
