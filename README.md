#                    Lesson 38

 - Data types (Ma'lumotlar turlari) ikki turga  
   bo'linadi.
    -- 1. Pirimitiv    2. Complex
          null            object
          undefined
          boolean
          number
          bigint
          string
          symbol
  
   Ma'lumot typ ini bilish uchun " typeof " aperator turudan foydalaniladi.

   !  null ni type ->object
     
     Misollar
     let a = 45;
     console.log(typeof a);

     TYPEOF OPERATOR //////////
     let a = 78;
     let a = "Hello";
     let a = true;
     let a = null;
     let a = undefined;
     let a = Symbol();
     let a = 45n;
     console.log(typeof a);

     Random yaratish

     let max = ...;
     let min = ...;
     let a = Math.floor(Math.random() * (max - min + 1)) + min;
     console.log(a);
    
    Math operatorlar
    
      num+str = str 
      num - / *  str(num) = num 
      str(num) / * - str(num) = num 
      others = NaN 