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

    public String[] contactInfo() {
        String[] contacts = {
            "LinkedIn: https://www.linkedin.com/in/bremen-jose-oliveira/",
            "Portfolio: https://jose-oliveira.de/",
            "Email: jose.oliv@hotmail.de"
        };
        return contacts;
    }

    public static void main(String[] args) {
        DeveloperProfile jose = new DeveloperProfile();
        jose.aboutMe();
        jose.techStack();
        jose.coreValues();
        System.out.println("Connect with me: " + Arrays.toString(jose.contactInfo()));
    }
}

