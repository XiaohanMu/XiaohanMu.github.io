+++
title = 'Projects'
date = 2024-09-16T04:02:13-05:00
draft = true
weight=3
categories = ["Career"]
summary = "Image Quilting Algorithm Implementation, EasyShare, Memorandum App"


+++
Here is a detailed overview of my projects:

### **EasyShare**
A web-based platform designed to facilitate file and message sharing between users. 
- Backend Development: Developed a robust file and message sharing web application using **Node.js** and **Express.js**, handling real-time requests with **asynchronous functions** and scalable **RESTful API endpoints**.

- Frontend Integration: Designed a responsive user interface with **HTML5**, **CSS3**, and **JavaScript**, incorporating **Bootstrap** for layout and styling. Implemented client-side file selection, validation, and messaging features.

- File Handling: Utilized **Multer** for file uploads with custom storage. Integrated **Fetch API** for seamless client-server communication.

- Cloud Deployment: Deployed the application using **AWS Elastic Beanstalk**, automating deployment pipelines with **AWS CLI** and **Docker** for containerization. Configured environment variables for secure key management and dynamic port allocation.


### **Image Quilting Algorithm Implementation**
Texture synthesis by seamlessly combining patches from a sample texture. 

- **Overlapping Patches**: Synthesized textures by randomly sampling square patches from a given sample. Selected the starting patch randomly. Iteratively sampled and filled overlapping patches based on the **sum of squared differences (SSD)** of the overlapping regions between the existing and sampled patches.

- **Seam Finding Algorithm**: Incorporated seam finding to remove edge artifacts from the overlapping patches by finding the **min-cost path** from the left to the right side of the patch.

{{< figure src="/images/sample_bricks.jpg" alt="Example small sample" width="200px" caption="Small Brick Sample" >}}
{{< figure src="/images/quilt_sample_cut.jpg" alt="Example" width="200px" caption="Quilted Texture result">}}





### **Memorandum App**
A task management application designed to help users organize and prioritize their tasks.

- **Login Page, Registration Page, and Navigation Bar**: Used **React** to implement a login and registration page. Designed and integrated a responsive navigation bar with **React Router**. Utilized React components for efficient rendering and state management.

- **Task Management System**: Developed a task management feature using **SQL** for data storage and retrieval, supporting task prioritization through a well-structured data schema. Managed task states and CRUD operations in **React**, optimizing performance through **React’s Context API** for global state management.



