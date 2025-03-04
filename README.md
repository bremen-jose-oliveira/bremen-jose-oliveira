# 👋 Hello, I’m José!

**Full Stack Developer | Tech Enthusiast | Lifelong Learner**

🌍 **From:** Lagos, Portugal 🇵🇹  
🌍 **Currently Living:** Germany 🇩🇪  

---

### 🚀 About Me  

```java
public class DeveloperProfile {
    private String name = "José";
    private String from = "Lagos, Portugal";
    private String currentLocation = "Germany";

    public void aboutMe() {
        System.out.println("Started in Portugal: bartender, assistant, meat cutter.");
        System.out.println("In Germany, gained expertise in logistics and warehouse management.");
        System.out.println("Full Stack Bootcamp Graduate now working as a Full Stack Developer.");
    }

    public void techStack() {
        String[] languages = {"Java", "TypeScript", "SQL", "Node.js", "React"};
        String[] devOpsTools = {"Git", "Jenkins", "SVN"};
        System.out.println("Languages & Tools: " + Arrays.toString(languages));
        System.out.println("DevOps & Version Control: " + Arrays.toString(devOpsTools));
    }

    public void coreValues() {
        System.out.println("Lifelong Learning: Always adapting to technology changes.");
        System.out.println("Problem Solving: Thrive on challenges with efficient, creative solutions.");
        System.out.println("Collaboration: Strong believer in teamwork.");
    }

    public void contactInfo() {
        String linkedIn = "[🌐 LinkedIn](https://www.linkedin.com/in/bremen-jose-oliveira/)";
        String portfolio = "[🌐 Portfolio](https://jose-oliveira.de/)";
        String email = "[✉️ Email Me](mailto:jose.oliv@hotmail.de)";
        
        System.out.println("Connect with me: " + linkedIn);
        System.out.println("Check out my work: " + portfolio);
        System.out.println("Reach out via email: " + email);
    }

    public static void main(String[] args) {
        DeveloperProfile jose = new DeveloperProfile();
        jose.aboutMe();
        jose.techStack();
        jose.coreValues();
        jose.contactInfo();
    }
}


