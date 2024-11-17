# İsmail Tarım - Computer Engineer

**Email:** [ismailtarim7@gmail.com](mailto:ismailtarim7@gmail.com)  
**LinkedIn:** [linkedin.com/in/ismailtarim](https://linkedin.com/in/ismailtarim)
**Phone:** +90 xxx xxx 8562
---

## Professional Summary

Innovative Computer Engineer specializing in AI-driven backend development, algorithm optimization, and database management. Currently pursuing a Bachelor's in Computer Engineering with a focus on AI integration. Known for technical leadership and a strong foundation in autonomous systems and robotics.

-Deeply passionate about becoming a full-stack developer, with a strong focus on the architecture and design of web applications.

-Actively learning both front-end and back-end technologies to gain a comprehensive understanding of the entire development process.

-I enjoy solving algorithmic problems on LeetCode, continually enhancing my expertise in data structures and writing efficient code.

-Committed to building efficient, scalable applications by expanding my knowledge of various technology stacks and software architecture.

---

## Core Skills

- **Programming Languages:** Python, JavaScript, C++, Java
- **Frameworks:** Django, Selenium, OpenCV, Next.js, Express.js, Firebase, BeautifulSoup, ROS
- **Tools:** Git, MATLAB
- **Databases:** MySQL, PostgreSQL

---

## Code Examples
```cpp
    vector<int> topKFrequent(vector<int>& nums, int k) {
        
        vector<int> res;

        if(nums.empty()){
            return res;
        }

        priority_queue<pair<int,int>, vector<pair<int,int>>, greater<pair<int,int>>> pq;
        unordered_map<int,int> m;
        for(auto num : nums){
            m[num]++;
        }

        for(auto &item : m){
            pq.push({item.second, item.first});
            if (pq.size() > k) {
                pq.pop();
            }
        }        
        
        while(!pq.empty()) {
            res.push_back(pq.top().second);
            pq.pop();
        }

        reverse(res.begin(), res.end());
        return res;
    }
```

## Experience

### **GDG On Campus IKCU – Core Team Member**  
*October 2024 - Present*  

### **ECO-ROVER – Robotics Developer, Programming Team Member**  
*October 2024 - Present*  

### **Beast Wear – Co-Founder, CTO**  
*March 2024 - Present*  
- Developed a scalable e-commerce platform using **Next.js** and **Firebase**.
- Integrated **shopier** and shipping APIs to streamline payment and logistics.

### **Brif Studio – Co-Founder, Backend-Prompt Engineer**  
*March 2023 - August 2023*  
- Engineered **AI-integrated backend systems** to automate presentation generation.
- Optimized **database management systems**, reducing data retrieval times by 40%.

### **TradeMonex – Backend Developer**  
*August 2022 – February 2023*  
- Built backend systems to support **blockchain-based applications**.
- Automated data processing workflows, reducing manual input requirements by 30%.

### **İzelman Robotics – Head of Programming**  
*June 2022 - Present*  
- Led development of autonomous and manual control systems for robotics, utilizing **AI** and **sensor fusion**.
- Designed and implemented control algorithms (e.g., **PID**) to enhance robotic performance.
- Facilitated hardware-software integration in complex robotics systems.
- Provided mentorship, contributing to improved team outcomes and technical skills.

### **Gökbörü ROV Team – Technical Lead**  
*October 2022 - April 2023*  
- Developed **ROS-Mavlink** protocols for real-time underwater operations.
- Implemented **AI-driven image processing** algorithms for sonar data, improving detection accuracy by 10%.
- Designed a proprietary **sonar system** with 360-degree scanning capabilities, enhancing environmental awareness.
- Utilized algorithms (**Sea-Thru**, **YOLO**) for underwater image correction and perception.

### **Volunteer Computer Vision Developer - AYA**
-Utilise deep learning, computer vision algorithms identify collapsed buildings from space and satellite imagery.
-Utilized Entropy Coding and Remote Sensing for pre-processing to optimize the processing of image analysis, allowing for faster turnaround times on identification efforts, Geographical Information Systems (GIS)
-Contributed to image labelling studies.
-Provided integral support to Twitter bot works used for backend processes and information extraction on an externally created website during disaster relief efforts.

### **Volunteer Educator - ECEV**
-Sum: Children aged 5-15; I gave FLL robotics training and awareness study, chess education for students over 100.

## Key Projects

**SearchStore: Web Scraping Application**  
**Technologies:** JavaScript, Fetch API  
- Built a web application for scraping and displaying data from various online stores using **JavaScript**.
- Implemented efficient data retrieval techniques with the **Fetch API** for real-time data display.

**Motion Extraction: OpenCV and Deep Learning**  
**Technologies:** OpenCV, Deep Learning, Numpy  
- Developed motion detection algorithms using **OpenCV** and integrated machine learning techniques.
- Enhanced detection accuracy through optimized algorithmic design and data preprocessing.

**AstroReis: AI-Powered Astrology Application**  
**Technologies:** Django, AI Techniques  
- Developed a **Django-based backend** for **AI-driven horoscope predictions**.
- Integrated multiple data sources to improve the accuracy and relevance of horoscopes.

---

## Education
**İzmir Katip Çelebi University**  
**B.Sc. in Computer Engineering**, Expected Graduation: June 2028

**Cihat Kora Anatolian High School**  
Science and Math, Graduated: June 2024

**Yusuf Kemalettin Perin Science High School**  
Science and Math, Attended until June 2022

**Certifications & Honors**
- Python Automation and Testing | National Association of State Boards of Accountancy (NASBA)
- Python Data Analysis | LinkedIn
- Advanced Prompt Engineering Techniques | LinkedIn
- Artificial Intelligence and Business Strategy | Project Management Institute (PMI)
- Critical Thinking for Better Judgment and Decision-Making | Project Management Institute (PMI)
  
---

## Languages

- **Turkish**: Native language
- **English**: C1 level
  - MEB(ministry of public education) Certified C1 
  - Izmir Katip Celebi University | Celebi Proficiency Test (scored 94%)
- **German**: A1 level 