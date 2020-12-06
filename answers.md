1) About 35 hours, most of it learning about Ratpack, Java, Docker and Gradle. I will get help to integrate Docker and Ratpack, I spend about 15 hours
reading docuentation and StackOverflow but I keep with this error at the moment of run it as a .jar:
	java.lang.BootstrapMethodError: java.lang.NoClassDefFoundError: ratpack/server/RatpackServerSpec

2) The Java.time package and his DateTimeFormatter tht I used in isValidDate method
	
    public static boolean isValidDate(String date){
        if(date.equals("") || date.equals(null)){
            return false;
        }

        DateTimeFormatter f = DateTimeFormatter.ISO_INSTANT;
        try {
            f.parse(date);
            return true;
        } catch (DateTimeParseException e) {
            return false;
        }
    }

3) I don't have a favorite, or at least in backend proceses.

4) Microservices, I18n and Serverless.

5) I haven't had to do this, most likely I will ask someone with experience in this situations about how to tackle the issue.  

6) I will add transormation between diferent Currencies using some external API to get the current convertion rates.

7)Myself on Json Format 
{
   "name":"Franco",
   "nationality":"Chilean",
   "age":28,
   "passions":[
      "Learning",
      "Basketball",
      "Pachamama",
      "DIY"
   ],
   "Features":[
      "Extrovert",
      "Loud",
      "Happy",
      "HardWorker",
      "Curious",
      "Good Teamate",
      "Good Leader",
      "Latino",
      "Honest",
      "Funny",
      "Chill"
   ],
   "Languages":[
      "Spanish",
      "English",
      "A lot of Coding ones",
      "A bit of Italian"
   ],
   "Hobbies":[
      "Yoga",
      "Ciclyng",
      "Mobility",
      "Cooking",
      "Reading",
      "Swimming",
      "History",
      "Geography",
      "Gardening"
   ],
   "Used to work as":[
      "Basketball Player",
      "Construction worker",
      "Full Stack Developer",
      "Substitute Math Teacher",
   ]
}

8) The joy that has on it
