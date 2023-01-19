# Initial SetUp

# API Planning
- Food (Food items & their details)
- Resturant (Resturant & their details)
- Menu (Menu & their details)
- Order (Order & their details)
- Image (Stroing all the imgs related to the zomato)
- Review (Storing all the list of reviews)
- User (User realted details, username, email n password)



jwt => JsonWebToken
Session Based Appln 
        > tokens
        > For the 1st time when we visit the appln we login or create a acc
                > at this pt of time -> a new JWT token will be generated
                > and if we revisit the appln after 1 day || 10 day ||10 months .. we don't need to pass the credentials
                        instead while making a req the generated JWT token ill be sent to the server
                > JWT will be stored in client or endusers browser (Cookise, localstorage)     

                > JWT also has expiration it depends on business perspective (1 day / 10 day // 10 years)  



hash & salting

prem1234 => hash() => @sadwasdd2!weasd => salt(5) => nbxcvrw!34221%$