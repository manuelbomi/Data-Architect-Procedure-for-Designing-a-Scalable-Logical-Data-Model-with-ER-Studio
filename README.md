# Data-Architect-Procedure-for-Designing-a-Scalable-Logical-Data-Model-with-ER-Studio


### **OVERVIEW**
In this discourse, we show the procedures of building a Logical Data Model (LDM) of a company's employee database including the Employees' names, Skills, Department, Agency that provides the Employee and the set of Training Courses for each Employee. The procedures is shown in form of process infographics.

In subsequent discourses, we shall show how to convert the LDM to a Physical Data Model (PDM) and how to write the PDM into a database. 

---

### **Background Discussion**
ER/Studio is data architecture, data modeling and database design software developed by IDERA, Inc. ER/Studio is compatible with multiple database platforms and is used to create and manage database designs, as well as to document and reuse data assets. It is also used to create LDMs, PDMs an dro reverse-engineer already deployed databases into their equivalent PDMs and LDMs.

---
After installing ER/Studio and obatining required licenses, Data Architects and Modelers can use the following procedures to create an LDM. 

---

#### Open the ER/Studio software, go to file and select new. Select Relational (for relational databases)

![Image](https://github.com/user-attachments/assets/8b5a656e-a0a1-4b98-b4b0-087ee42a9896)

---

#### Right click main model and click Create Submodel
![Image](https://github.com/user-attachments/assets/18011a1d-d205-4be2-8be4-41f92ee02cc7)

---
#### Name the submodel as 'Training'
![Image](https://github.com/user-attachments/assets/364e3367-8a27-4037-9751-40d0d29df19f)

---
#### Go to shapes and select Title Block
![Image](https://github.com/user-attachments/assets/9cad297b-12e8-461a-b8fc-55e6e0b17dbf)

---

####  Add a Business Data Object and name it Employee

![Image](https://github.com/user-attachments/assets/7d754d97-0728-4a2a-8210-ad6d2591d050)

---

#### Right click on Business Data Object and select New Business Data Object
![Image](https://github.com/user-attachments/assets/3f311e3f-2c30-449a-aa12-a0238910cdce)

---

#### Name it Department
![Image](https://github.com/user-attachments/assets/4d57b49b-e8d4-49a7-97e8-bd5f081b2500)

---

#### Create more Business Data Objects and name them

![Image](https://github.com/user-attachments/assets/e07e7bd8-5c3e-49ff-8fdc-acb054e668fe)

---
#### Create sub entities under Employees and name them
![Image](https://github.com/user-attachments/assets/abeb23a5-0992-4197-b172-2a28a854b5df)

---

#### Create more entities and name them

![Image](https://github.com/user-attachments/assets/c8f2b1ec-b6b9-4b1d-a71c-9bd7e4a807d5)

---
#### To add our entities to the Business Data Objects: press ctrl and click on all the entities

![Image](https://github.com/user-attachments/assets/35d122cf-5337-4186-a360-92a4e365106f)

---
#### Right click and add to the Business Data Object
![Image](https://github.com/user-attachments/assets/aba70986-f558-4325-b09d-2f79b594f294)

---
#### We can now edit the Business Data Object

![Image](https://github.com/user-attachments/assets/46504412-2fc9-4d20-a071-e8063c9ec5e0)

---
####  Edit the Business Data Object
![Image](https://github.com/user-attachments/assets/7f10e4f2-88a0-48a4-813a-b15cb6209edd)

---
#### Employee is the most important entity in  Business Data Objects (BDOs). Set it as the Anchor object

![Image](https://github.com/user-attachments/assets/028e1258-d0c5-4022-9abd-9c41b3e14a97)

---
#### Repeat same for other BDOs. Select and set the Anchor object
![Image](https://github.com/user-attachments/assets/613e6cea-9bb7-4929-9a8c-fe476a81fdcb)

---
#### Repeat same for other BDOs. Select and set the Anchor object
![Image](https://github.com/user-attachments/assets/c174d114-1a9a-4824-8470-ac1265b153f5)

---
#### Click and type primary keys for each object e.g. Employee Number
![Image](https://github.com/user-attachments/assets/c3e9f4aa-6fa1-45eb-a5c0-2b6161e78fee)

---

#### Shift + click inside Employee Number and use arrow down to type non key attributes
![Image](https://github.com/user-attachments/assets/e170abd5-87c3-4dd5-8c48-0d4a0ddbfdb6)

---
#### Click inside Employee Number and use arrow down to type non key attributes
![Image](https://github.com/user-attachments/assets/9506b0e0-c1c1-4c87-b68e-a01e1ee5383e)

---
#### Click below the line and type more non-key attributes
![Image](https://github.com/user-attachments/assets/0131e34a-7ed3-41bb-a079-38f81b2c8fbe)

---
#### Each attribute can be edited by double clicking on them
![Image](https://github.com/user-attachments/assets/4682cdbd-743e-4995-b356-bd3dd45ff5d0)

---

#### Developers can also double click and use the 'Add' button to add attributes to the Entities if the click + shift option doesn't work

![Image](https://github.com/user-attachments/assets/d4a0478c-7acd-4993-9439-3f5c19227e3a)

---
#### Add other entities attributes

![Image](https://github.com/user-attachments/assets/5274a394-3e5e-4c27-a43e-cf852df3f0b4)

---
#### Click to specify the relationships. Select the Complete Subtype Cluster type
![Image](https://github.com/user-attachments/assets/d8a1c2f4-99d6-4255-a34e-d87e8269706b)

---
#### Establish the Employee relationships

![Image](https://github.com/user-attachments/assets/386ed09b-8345-4854-b4aa-df137576df76)

---

![Image](https://github.com/user-attachments/assets/f085d9d8-5120-4874-a095-59e85a645df9)

---

![Image](https://github.com/user-attachments/assets/ba99adb1-1bda-4bfe-8101-f90db8570934)

---

![Image](https://github.com/user-attachments/assets/cae1e73d-9958-42a0-aad7-4cdd0571e59e)

---

![Image](https://github.com/user-attachments/assets/1b85d706-8712-4192-b264-dd3c2a6cb267)

---

![Image](https://github.com/user-attachments/assets/ceb76fb7-9829-4d3f-92f3-d16c2e43f634)

---

![Image](https://github.com/user-attachments/assets/57b1423b-9353-4703-8078-2a5ff6eb94a1)

---

![Image](https://github.com/user-attachments/assets/4e8102a2-43fe-4cca-917f-d4dfd1a329ac)

---

![Image](https://github.com/user-attachments/assets/8d76b9c8-56f1-4bc3-8822-f9b692bdc41c)

---

![Image](https://github.com/user-attachments/assets/c6ff1534-e99d-430d-aec4-57854aba9fed)

---

![Image](https://github.com/user-attachments/assets/479f676e-f394-4c6e-b986-6880847734c8)

---

![Image](https://github.com/user-attachments/assets/7753c54a-72d0-4818-8103-29b0e34ee53c)

---

![Image](https://github.com/user-attachments/assets/bb6aec76-f77b-42c6-81de-521e96b386d2)

---

![Image](https://github.com/user-attachments/assets/aacfbd61-aeff-4336-a0ff-24f7079f77be)

---

![Image](https://github.com/user-attachments/assets/1157a50f-a7a5-4e0e-bc58-5d2023d49f7d)

---

![Image](https://github.com/user-attachments/assets/4e43c25b-539a-4c46-9d50-dc246b332fa8)

---

![Image](https://github.com/user-attachments/assets/cbe1bd3e-f23a-4594-bf2e-67ed73832f34)

---

![Image](https://github.com/user-attachments/assets/8bb25e49-3f6b-4b57-a3c5-f4f219d1cd83)

---

![Image](https://github.com/user-attachments/assets/c0834421-04ae-48a8-a312-a9be17001301)

---

![Image](https://github.com/user-attachments/assets/d8780ae2-228c-42cb-88f3-7490e8995ed0)

---

![Image](https://github.com/user-attachments/assets/59f9d6ed-034a-4afa-a0a8-e5cffbce3c31)

---

![Image](https://github.com/user-attachments/assets/59e6ef80-f74d-44ce-b5c7-614d77a960ac)

---

![Image](https://github.com/user-attachments/assets/590bfc63-307d-44e7-b9da-4623b8e201ca)

---

![Image](https://github.com/user-attachments/assets/315c251e-03e5-4f2d-bbf1-bd4072575088)

---

![Image](https://github.com/user-attachments/assets/5e27e004-1419-47f1-ab5a-04dfcf5e1eef)

===

![Image](https://github.com/user-attachments/assets/99ca2f1a-8902-484a-9ad6-e956d21ac117)



---
Thank you for reading through

---

Author's Background

```

Author's Name:  Emmanuel Oyekanlu
Skillset:   I have experience spanning several years in developing scalable enterprise data pipelines, architecting enterprise data solutions, data engineering, deep learning and LLM applications as well as deploying solutions (apps) on-prem and in the cloud. I can be reached through: manuelbomi@yahoo.com
Website:  http://emmanueloyekanlu.com/
Publications:  https://scholar.google.com/citations?user=S-jTMfkAAAAJ&hl=en
LinkedIn:  https://www.linkedin.com/in/emmanuel-oyekanlu-6ba98616
Github:  https://github.com/manuelbomi

```

[![Icons](https://skillicons.dev/icons?i=aws,azure,gcp,scala,mongodb,redis,cassandra,kafka,anaconda,matlab,nodejs,django,py,c,anaconda,git,github,mysql,docker,kubernetes&theme=dark)](https://skillicons.dev)



