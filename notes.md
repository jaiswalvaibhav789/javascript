#Validation =>
    Validations are used to validate the user to fill the criteria.
    There are two Two Types of Validation available.
    1.Client Side Validation
        Client Side Validation are those validation 
        which is applied at the client side (frontend).
        1.Required =>likha hai ya nhi
        2.length =>kitna likha
        3.pattern =>kya likha hai kitna likha hai


    2.Server Side Validation 
        Server side Validation are those validation 
        which is apllied at the server side (backend).
        It is the more secure way to integrate the validation.
        1.Required 
        2.length
        3.pattern


Regular expression ===>>
        Regular expression is a set of character which is used for search a pattern in javascript.
        Syntax->starting => /^
        ending => $/
        range => []
        limit =>{}
        other => + . \
        Ex => if we are check a name for matching the 
        pattern
            let a = /^[a-zA-Z]{3,30}$/
        Ex => if you want to check mobile number
            let a = /^[0-9+]{13}$/
        Ex => if you want to check aadhar number
            let a = /^[0-9]{12}$/
        Ex => if you want to check email
        const a = /^[a-zA-Z0-9._]+@+[a-zA-Z]+\.+[a-zA-Z]$/
