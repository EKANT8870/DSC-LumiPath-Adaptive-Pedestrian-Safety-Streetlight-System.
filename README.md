# DSC-LumiPath-Adaptive-Pedestrian-Safety-Streetlight-System.
Overview : Conventional streetlights operate on fixed schedules, remaining fully illuminated on empty nocturnal roads and wasting significant electricity. LumiPath is a low-cost, smart street lighting prototype that provides light on demand, reducing energy consumption while improving pedestrian safety.

System Architecture & Hardware: The system is built around an Arduino Uno microcontroller integrated with a comprehensive sensor suite:
Light Detection: An LDR (Light Dependent Resistor) sensor manages automated day-to-night transitions, utilizing a dual-threshold hysteresis band (900 for night mode, 850 for day mode) to entirely eliminate switching flicker.   
Motion & Proximity Detection: Dual infrared (IR) obstacle sensors monitor pedestrian presence to provide immediate activation coverage.   
Mobility Tracking: An HC-SR04 ultrasonic sensor continuously calculates the real-time distance and approximate speed of approaching objects.  
Emergency Safety Feature: An independent push-button toggle triggers an SOS alarm buzzer to support individual security.   
Visual & Software Feedback: Output paths consist of a tricolor LED array (green, yellow, red) acting as the lamp unit, alongside a real-time web dashboard (Adaptive Streetlight Interactive Visualizer) that displays live sensor metrics, system states, and lighting cones.   
Impact & Smart City Relevance :
Aligned with the Smart Cities Mission and UN Sustainable Development Goals (SDGs 3, 7, 9, 11, and 13), LumiPath ensures that illumination is provided strictly "on-demand"—remaining completely off during the day and on empty nocturnal roads. Estimated performance metrics indicate massive energy savings ranging from 49% to 89% per pole annually (depending on traffic frequency), substantially lowering municipal carbon emissions while prioritizing urban pedestrian safety and smart infrastructure automation.   
