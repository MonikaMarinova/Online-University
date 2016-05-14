# Admin class represents an Administrator. Contents constructor, getters, setters and Override toString.

#Admin File Manager class contains method which saves a new admin\lecturer\student in admins\lecturer\student.txt file, method which finds admin\lecturer\student by its ID and deletes it. The method makes temporary text file in which saves all admins from the original file without the admin with ID equal to the wanted one, then renames the temporary file and deletes the original and method which reads from the console and creates new Admin\Lecturer\Student.

#Admin Operator class contains method which uses switch-case construction and operates with the methods from AdminFileManager Class.

#Lecturer class represents an Lecturer. Contents constructor, getters, setters and Override toString.

#Lecturer File Manager class contains method wich finds student by its Faculty Number. Writes studentFacultyNumber + "\t"+ studentName+ "\t" + studentMark in text file with name Lecturer.getLecturerName() + Lecturer.getUniversityClass(). Writes Lecturer.getLecturerName() + "\t" + Lecturer.getUniversityClass() + "\t" + studentMark in text file with name wantedStudentFacultyNumber+"Marks" and method which reads from the console the content of the University Class and writes it in text file with name Lecturer.getLecturerName() + Lecturer.getUniversityClass() + "Class".

#Lecturer Operator class which contains method with switch-case construction and operates with the methods from LecturerFileManager Class.

#Log in class which contains method which checks whether a user exists and if it doesn't it creates a new registration(saves the username and password in text file registratedUsers.txt), method which checks whether a user exists and if it exists start the authorization in University class and method uses switch-case construction and operates with the methods from Login Class.

#Exceptions: No Such Admin Exception, No Such Lecturer Exception, No Such Student Exception.

#Student class represents an Student. Contents constructor, getters, setters and Override toString.

#Student File Manager class  contains method which finds text file with name Student.getStudentFacultyNumber() and prints the content of the file on the console and method which finds text file with name nameOfLecturer + nameOfUniversityClass + "Class" and prints the content of the file on the console.

#Student Operator class which contains method with switch-case construction and operates with the methods from LecturerFileManager Class.


