# Redis

  This redis file is on the Library management application which is designed with the details about students, staff, books and details about book issual.
It is decided that the database should contain four entity types :
      
        1.Student details ,abbreviated "STUD_DETAILS".
        2.Book details, abbreviated "BOOKS".
        3.Staff details, abbreviated "STAFF_DETAILS".
        4.Book issual details, abbreviated "BOOK_ISSUAL".
        
 The next step in design process is determining attributes for each entity:
        
        1.The STUD_DETAILS entity maintains the student id, student name and department.
        2.The BOOKS entity maintains the book id, title of the book, author and year of publication.
        3.The STAFF_DETAILS maintains staff name, staff id and the department.
        4.The BOOK_ISSUAL maintains book id, access id, issual date and the return date.
        
 The data is stored as a set with entity name as set names and attribute name as key followed by values .Each set has over three or four attributes with values associated with it.      
