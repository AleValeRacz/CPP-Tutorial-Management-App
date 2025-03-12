# C++ Tutorial Management Application  

This application, built using **C++ and Qt**, provides a structured way to manage C++ tutorials, supporting both **admin** and **user** modes. It follows **object-oriented programming (OOP) principles**, while being designed using **Layered Architecture**, for better organization and scalability.  

## Features  

### 🔹 Admin Mode  
- Add, remove, and edit tutorials, with data stored in a text file  
- Undo and redo actions to revert or restore changes  

### 🔹 User Mode  
- Create a **watchlist** by adding or removing tutorials from the available collection  
- Search for tutorials by **presenter** and open their links in a browser  
- Navigate through tutorials, giving a **like** after viewing  
- View the watchlist in a **table format** or export it as **CSV or HTML**  

## OOP Principles Applied  
- **Encapsulation**
- **Inheritance**
- **Polymorphism**
- **Abstraction** 

## Architecture  
The application follows a **Layered Architecture**, separating the system into distinct modules by domain:
- **Domain Layer**: Core logic, entities, and models  
- **Repository Layer**: Data access, file handling, and storage  
- **Controller Layer**: Bridges the business logic and UI components  
- **UI Layer**: Handles user interaction and presentation using Qt  
 
