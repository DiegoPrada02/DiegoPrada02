from pathlib import Path

readme_content = """# 👋 Hi, I'm Diego Prada Ortiz  

🎯 **Software Engineer | Full-Stack Developer | AI Enthusiast**  

I’m a **Software Engineer** and proud **graduate of Florida International University** with a **B.S. in Computer Science**.  
I’m passionate about building scalable, user-focused solutions across web, mobile, and AI platforms — combining creativity with data-driven development.  

---

## 🧠 About Me  

- 💻 Experienced in **Python, Java, JavaScript, and React** for full-stack development.  
- 🧩 Skilled in designing and optimizing **database systems** (MySQL, MongoDB) and leveraging **Firebase** for scalable apps.  
- 🚀 Passionate about **AI integration, automation, and intuitive user experience design**.  
- 🌎 Bilingual in **English and Spanish**.  
- 🤝 Member of the **Society of Hispanic Professional Engineers (SHPE)**.  

---

## 🧰 Tech Stack  

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Unity3D](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Photoshop](https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## 🧩 Featured Projects  

### 🏥 [Hospital Database](#)  
*Java • MySQL*  
- Developed and deployed a **hospital management system** that reduced data processing time by **30%**.  
- Designed a robust **MySQL database** to enhance record security and accessibility.  
- Built an intuitive **Java GUI** that improved staff workflow and operational efficiency.  

---

### ✍️ [Collaborative Story Builder](#)  
*Unity3D • Firebase • Google Gemini AI • MyMemory API*  
- Created a **cross-platform storytelling app** enabling real-time, multilingual collaboration.  
- Implemented **Firebase Authentication** and **Firestore** for secure and scalable user data management.  
- Integrated **AI-driven story continuation** and **instant translation** for inclusive storytelling across languages.  
- Achieved **120+ user-created stories** over 7 agile sprints, emphasizing collaboration and creativity.  

---

## 💼 Professional Experience  

### 🚚 Logistics Systems Analyst — *Link’t Systems LLC*  
*Aug 2021 – Present*  
- Analyzed logistics processes to identify inefficiencies, reducing transportation and inventory costs.  
- Implemented and optimized **logistics management software** to improve shipment visibility by 20%.  
- Integrated **WMS systems** for real-time reporting, automation, and data accuracy in supply chain operations.  

---

### 🛠️ Customer Service Specialist — *The Home Depot*  
*Aug 2024 – Present*  
- Resolved 200+ customer inquiries monthly with a **90%+ satisfaction rate**.  
- Reduced repeat technical support requests by **20%** through proactive issue resolution and customer education.  

---

## 🌟 Soft Skills  

- Leadership • Teamwork • Attention to Detail  
- Time Management • Communication • Problem Solving  

---

## 🎓 Education  

**Bachelor of Science in Computer Science**  
**Florida International University** — *Graduated 2025*  

---

## 📫 Connect With Me  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/diegopradaortiz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DiegoPrada02)
[![Email](https://img.shields.io/badge/Email-diegopradadev@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diegopradadev@gmail.com)

---

⭐️ *"Code with purpose. Design with empathy. Build for impact."*  
"""

# Save the README content to a file
output_path = Path("/mnt/data/README.md")
output_path.write_text(readme_content)

output_path
