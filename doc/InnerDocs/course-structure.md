# Basic Hierarchy


This will be our basic structure. The Course class is the main class that encapsulates the entire course structure. Identification, Content, and Implementation are three classes contained within the Course class, representing different aspects of the course.  Attributes within each class represent the data or properties. Details and the explanations of each attribute can be found in the presentation.


```{figure} ../images/Course-Str.png
Important to follow this structure.
```

## Course Identification
-  **Name:** Represents the name of the course.
-  **Type:** Indicates the type of the course, whether it's user interface, infrastructure, interdisciplinary, or domain dependent.
-  **Content:** Contains the table of contents specifying what will be covered in the course.

## Course Content
-  **TextResource:** Represents textual resources associated with the course.
-  **Presentations:** Includes presentation materials for the course.
-  **Videos:** Contains video resources related to the course.
-  **GitResource:** Represents resources available on Git (a version control system).
-  **ContentCreator:** Indicates the creator of the course content.

## Course Implementation
-  **Type:** Specifies whether the course is asynchronous or synchronous, and if synchronous, whether it is online or face-to-face.
-  **Infrastructure:** Describes the technological setup or framework used for the course.
-  **Instructor:** Represents the instructor or facilitator of the course.
-  **Location:** Indicates the physical or virtual location where the course is conducted.
-  **TimeAndSchedule:** Provides information about the schedule and timing of the course.
