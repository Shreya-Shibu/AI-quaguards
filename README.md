# AI-quaguards

---

# **AI-Powered Solar-Powered Beach Cleaning Bot**

## **Problem Statement**:
This project is an innovative approach to tackling beach pollution using advanced robotics, artificial intelligence, and sustainable energy. The AI-Powered Solar-Powered Beach Cleaning Bot is a simulated autonomous robot designed in **Webots** that performs efficient beach cleaning while minimizing environmental impact. As existing cleaning bots are manually operated, we incorporated an autonomous cleaning bot.

## **Key Features**
- **Autonomous Operation**: Equipped with AI, the bot can navigate the beach, avoid obstacles, and efficiently clean littered areas without human intervention.
- **Trash Detection and Classification**: Uses computer vision algorithms to detect and classify different types of trash (e.g., plastic, metal, organic).
- **Solar-Powered**: Operates sustainably by harnessing solar energy, making it eco-friendly and cost-effective.
- **Obstacle Avoidance**: Integrated with sensors (e.g., LiDAR, ultrasonic) to avoid obstacles and ensure smooth navigation.
- **Real-Time Monitoring**: Live dashcam video feed,  robot tracking, and operational data monitoring.

## **How It Works**
1. The bot navigates a simulated beach environment in Webots, powered by AI and equipped with virtual sensors and cameras.
2. Trash detection and segregation algorithms classify and dispose of collected waste in appropriate compartments.
3. Solar energy powers the bot in the simulation, demonstrating sustainability.

## **Use Case**
This project addresses the growing issue of beach pollution by providing an autonomous and sustainable solution. It can be scaled for real-world implementation to maintain cleaner beaches, protect marine life, and promote eco-friendly practices.

## **Tech Stack**
- **Programming Languages**: Python 
- **Webots**: The simulation model of the cleaner bot was designed in it.
- **Yolov10**: It was used to train the base model to differentiate between obstacles and waste.
-**roboflow annotation**: It was used to create the dataset to train the Yolov10 base model.

## **Future Developments**
While this prototype demonstrates the basic functionality of navigation, trash detection, and monitoring, some planned features are yet to be implemented:

- **Trash Segregation and Disposal**: The bot currently collects trash, but segregation into categories (e.g., plastic, metal, organic) and proper disposal mechanisms need to be developed.
- **Enhanced Obstacle Avoidance**: Fine-tuning the navigation logic for complex and crowded beach environments.
- **Real-World Deployment**: Transitioning from simulation to a physical prototype, including hardware integration and field testing.
- **Advanced Analytics**: Adding data analytics features, such as heatmaps of litter density or reports on cleaning efficiency.
- **Website Features**: Integrating predictive maintenance alerts, AI-based recommendations for manual intervention through a website.
---
