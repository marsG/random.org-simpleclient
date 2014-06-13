### random.org-simpleclient


#####java http client to get random integers in varying formats from random.org.<br/> random.org is a true random number service.

###### -supports random.org's guidelines for automated clients</strong>

    - long timeout value for your requests
    - quota is checked before making a request
    - e-mail address as the user-agent field
    
    

###### //Here is some sample code:
     RandomIntegerClient cl = new RandomIntegerClient("youremail@foo.bar");
     //get a list of 20 random integers(base 10) in the  [1,100] interval.
     List<String> myRandomIntegers = cl.getRandomIntDecimal(1,100,20);
     //supports base 2, 8, 10, and 16.
    
