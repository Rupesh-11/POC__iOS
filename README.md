# POC__iOS
    1. Registration & Login screen 
        a. Screen design should be as shown below
        
        1. Registration & Login screen 
    a. Screen design should be as shown below
    
   
   
   ![image](https://github.com/Rupesh-11/POC__iOS/assets/59641297/450a0e5b-3597-430c-a717-a5dbdf8658c7)

    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    

    b. Validations should be applied to each field. (Email should take email input, password should be 8 characters long).
    c. Error should be shown if user does not input any field or enters invalid data.
    d. After registration save all values in local database.
    e. On Login user inputs should be present in database. If user inputs are not present in database then user should not be able to login.
    f. Show error if user is unable to login.
 2. Country list screen
    a. Once user logs into the app show all country list with flag icon in list view.
    b. Use the following URL to get list of all countries along with flag.
       cdn.jsdelivr.net/npm/country-flag-emoji-json@2.0.0/dist/index.json
    c. From the below object use “name” & “image” fields to display name & image in list view.
{
"name": "Ascension Island",
"code": "AC",
"emoji": "🇦🇨",
"unicode": "U+1F1E6 U+1F1E8",
"image": "https://cdn.jsdelivr.net/npm/country-flag-emoji-json@2.0.0/dist/images/AC.svg"
}




![image](https://github.com/Rupesh-11/POC__iOS/assets/59641297/dafec8ab-1d2d-43c7-b40c-68489a337aa0)







































3. Details screen.
    a. On click of country list item show country details in details screen.
    b. From above json response display “code” & “Unicode” fields on 3rd screen.
    
    Uses Swift for iOS
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        

       
