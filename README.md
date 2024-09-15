## Hey there, I'm Mohamedamin! 👋

👋 Prev. SWE Intern @ John Deere 🌟.

🎓 Pursuing a Bachelor of Science in Computer Science at the University of Wisconsin-River Falls. Expected graduation date 05/2025.

Previously Interned at John Deere, part of the Deere Financial Team as a full stack Software Engineer at the HQ. You can contact me at mohamedamin204080@gmail.com

💻 Technical Proficiency: 
Java, C#, JavaScript/HTML/CSS, SQL, C and Python. Experienced in technologies such as ReactJs, NodeJs, ExpressJs, Spring Boot Redux, MySQL, Microsoft SQL Server, DynamoDB, AWS, GIT/GitHub/GitLab, Linux, Intellij, Eclipse, and VS Code. 

public class FunReadMeAnimation {
    public static void main(String[] args) throws InterruptedException {
        String message = " Welcome to my GitHub! ";
        String blankSpace = " ".repeat(50); // Adjust this for desired space
        String displayMessage = blankSpace + message;

        while (true) {
            System.out.print("\r" + displayMessage);
            displayMessage = displayMessage.substring(1) + displayMessage.charAt(0);
            Thread.sleep(200); // Adjust for speed
        }
    }
}


