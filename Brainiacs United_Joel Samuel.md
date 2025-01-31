# Breathe Easy: Revolutionizing Nicotine Exposure Tracking with Wearable Technology
## Team Description:
### Team Lead
* <ins>Joel Mathew Samuel</ins>

  S3, B.Tech Computer Science and Engineering

  *SAINTGITS COLLEGE OF ENGINEERING*

### Team Members
* <ins>Jerit Reji</ins>

  S3, B.Tech Computer Science and Engineering

  *SAINTGITS COLLEGE OF ENGINEERING*

* <ins>Shane Varghese Jacob</ins>

  S3, B.Tech Computer Science and Engineering

  *SAINTGITS COLLEGE OF ENGINEERING*

* <ins>Sreekrishnan M.</ins>

  S3, B.Tech Computer Science and Engineering

  *SAINTGITS COLLEGE OF ENGINEERING*

## Problem Overview:
"Every breath taken, every life lost" `Nicotine addiction` claims millions of lives worldwide, enslaving individuals in a vicious cycle of craving and relapse. Despite the Dangers the struggle to quit is real:
* **70% of smokers** unable to overcome the grip of nicotine.
* **The absence of real-time monitoring** and personalized support hinders the journey to a smoke-free life.
### Healthcare Burden
Smoking causes people to have many chronic illnesses such **<u>Lung cancer</u>**,**<u> Heart disease</u>** and  <u>**chronic obstructive pulmonary disease (COPD)</u>**.
Smoking kills around 8 million people each year, with an estimated 1.3 million non-smokers who are exposed to `second-hand smoke`.
### Social and Family Issues
Second-hand smoke exposure affects non-smokers, especially children, while smoking-related illnesses strain family relationships.
### Economic Consequences
Smoking results in significant economic losses due to productivity decline, absenteeism, and healthcare expenses.
### Addiction and Mental Health
Nicotine addiction perpetuates a cycle of dependence, linked to increased risk of mental health issues.

#### The absence of effective solutions leaves individuals trapped in a haze of addiction. It's time for innovation to break the cycle of nicotine addiction and create a smoke-free future.

## Solution Overview:
### BreatheSafe
Introducing **BreatheSafe**, an innovative wearable device designed to revolutionize the fight against nicotine addiction. By providing real-time monitoring and personalized support, **BreatheSafe** empowers individuals to take control of their journey towards a smoke-free life. This innovative solution addresses the critical gaps in traditional methods, offering a comprehensive approach to overcoming nicotine dependence and promoting long-term health and well-being.

**BreatheSafe** collects data about the nicotine presence around the surroundings and shows areas where the nicotine levels are higher.

- It processes real-time data received from users and updates over every few minutes.
- BreatheSafe contains `Vanadium Dioxide` sensors which when exposed to a nicotine atmosphere change the conductivity of the current flowing and this change is equivalent to nicotine concentration
- The chip then transmits the digitized signal to a smartphone through Near-field-Communication(NFC).
- Then the data is tuned by our ML model to be shown to the users where all are nicotine levels are higher and showing alternate routes.

### Features of **BreatheSafe**

- It uses nicotine to detect tobacco exposure and it is a prominent ingredient in tobacco products which can be measured in sweat.
- BreatheSafe is `portable` and easy to wear.
- Provides continuous monitoring of nicotine levels.
- The results can be viewed directly through a smartphone.

## How It Works:
### Wearable, Battery-Free Nicotine Sensor Can Monitor Your Exposure to Smoke and Vape Mist
Our innovative sensor harnesses the power of near-field communication (NFC) to track nicotine exposure in real time, without the need for batteries. This compact, wearable device uses cutting-edge technology to help individuals monitor their nicotine levels with minimal difficulty.

![image](https://hackster.imgix.net/uploads/attachments/1383449/image_DjIloh3QwV.png?auto=compress%2Cformat&w=830&h=466.875&fit=min&dpr=1)

**Components:**

1. **Vanadium Dioxide (VO₂) Sensor:** A highly sensitive material that reacts to nicotine, altering its electrical characteristics.
2. **Amplifier:** Boosts the sensor's signal, ensuring accurate and reliable detection.
3. **NFC Chip:** Wirelessly transmits data to a smartphone or NFC-capable device, enabling seamless monitoring.

__Technical Advantages:__

- **Battery-Free:** Eliminates the need for battery replacement or recharging.
- **Real-Time Monitoring:** Provides instantaneous updates on nicotine exposure.
- **Compact Design:** Wearable device for unobtrusive monitoring.
- **High Sensitivity:** Accurately detects nicotine levels, even in small concentrations.

__Technical Specifications:__

- **Sensor Material:** Vanadium Dioxide (VO₂)
- **Sensitivity:** upto 5 meters.
- **Power Consumption:** Zero (battery-free)

> Nicotine can bond covalently to a thin film of VO2. Hence, depending on the nicotine concentration the conductivity of the film changes. The device detects the change in conductivity, amplifies the signal, and then transmits it wirelessly to a smartphone.
### Key Software Components:

![Screenshot (45)](https://github.com/user-attachments/assets/4a8d07b3-91f7-432c-be66-be5517088e80)

1. **Mobile Application:** Developed using React Native, our mobile app enables users to track their nicotine exposure levels, receive alerts, and access personalized insights.
2. **Data Processing:** Utilizing Python and TensorFlow, our backend processes sensor data, applying machine learning algorithms to detect patterns and trends.
3. **Cloud Services:** Amazon Web Services (AWS) provides a secure and scalable infrastructure for data storage, processing, and analytics.
4. **API Integration:** RESTful APIs enable communication between the mobile app, backend, and cloud services, ensuring a cohesive user experience.
5. **Data Visualization:** Tableau and D3.js libraries are used to create interactive, user-friendly dashboards for data visualization and insights.
## Beneficiaries:

![960f5f2a-029e-4a22-a807-bf512475df6a](https://github.com/user-attachments/assets/1d8abce9-b492-4561-b96c-011f5ffdd43f)

**Low-income families:** Due to the use of advanced technologies in the device, it could potentially have a high initial cost but families with low income can receive subsidies and grants from the government to cover costs. Further research can develop more cost-effective and basic models allowing a widespread usage of the sensor. These factors aid low-income families to afford this device as they tend to be uneducated on the extremely negative effects of nicotine and could be around areas with potentially high nicotine exposure unknowingly.

**Public Health Market:** It can aid in monitoring and controlling outdoor air quality, particularly in areas where smoking is banned or restricted, ensuring compliance with regulations and promoting healthier environments.

**Industries:** Businesses could use the sensor to maintain smoke-free environments, enhancing employee well-being and potentially reducing healthcare costs.

Portable nicotine sensors are being developed as an alternative, but the two that have been reported are impractical because they rely either on the presence of sweat or sunlight to function.

## Potential Impact
Our innovative nicotine sensor has far-reaching potential to positively impact individuals, communities, and society as a whole.

### Social Impact:

- Reduced exposure to second-hand smoke, creating a healthier environment for families and vulnerable individuals, such as children.
- Stronger, healthier relationships due to reduced smoking-related diseases.
- Empowered individuals seeking cessation, with real-time feedback and tracking progress.

### Health Impact:

- Enhanced support for smokers seeking help, with personalized interventions and more effective quit plans.
- Healthcare professionals better equipped to support patients, with data-driven insights into nicotine cravings and triggers.
- Reduced smoking-related diseases, leading to improved overall health and well-being.

### Economic Impact:

- Decreased healthcare costs associated with smoking-caused diseases.
- Increased productivity and reduced absenteeism, benefiting the economy.
- Potential reduction in smoking-related costs.

### Environmental Impact:

- Reduced cigarette consumption, leading to fewer cigarette butts littering the environment.
- Cleaner streets and water bodies, contributing to a healthier environment.

### Hotspot Detection and Route Optimization:

By leveraging machine learning algorithms and data from our nicotine sensor, we can:

- Identify areas with high nicotine levels, creating **hotspots** of exposure.
- Provide users with personalized route suggestions, avoiding high-nicotine areas and promoting healthier walking routes.

>Example: A person going for a walk can wear our device, continuously monitoring nicotine exposure. The data is fed into a machine learning model, which generates a personalized route for their next walk, avoiding areas with high nicotine levels.

### Data-Driven Insights:

Our sensor can provide valuable data for:

- **Healthcare professionals**, to inform personalized deaddiction programs.
- **Public health agencies**, to enforce effective public health policies and regulations.
- **Researchers**, to better understand nicotine addiction and develop more effective interventions.

>By harnessing the power of our innovative nicotine sensor, we can create a healthier, happier, and wealthier society, breaking the chain of addiction and promoting a smoke-free future.
## Conclusion:
In conclusion, our innovative nicotine sensor has the potential to revolutionize the way we approach smoking cessation and nicotine exposure. By harnessing the power of `near-field communication` and `vanadium dioxide sensor technology`, we can provide individuals with real-time feedback and tracking, empowering them to take control of their nicotine levels. With its compact, wearable design and battery-free operation, our sensor is poised to make a significant impact on public health.

We envision a future where families can breathe easier, free from the harmful effects of second-hand smoke. Where healthcare professionals can tailor their support to meet the unique needs of each patient. And where communities can come together to create a cleaner, healthier environment for all.

Our sensor is just the beginning. With it, we can unlock a world of possibilities for positive change. Let's work together to make that vision a reality, one step at a time.
