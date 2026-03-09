# Java
Java crt
mkdir MyJavaProject
cd MyJavaProject
MyJavaProject/
│
├── src/
│   └── Main.java
├── README.md
└── .gitignore
mkdir src
cd src
touch Main.java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, GitHub!");
    }
}
cd ..
touch README.md
# MyJavaProject

A simple Java project to demonstrate pushing code to GitHub.

## Structure
- `src/Main.java` - main Java program

## How to Run
1. Compile: `javac src/Main.java`
2. Run: `java -cp src Main`
touch .gitignore
*.class
*.jar
*.log
git init
git add .
git commit -m "Initial commit with Java project and README"
MyJavaProject.
git remote add origin <your-github-repo-url>
git branch -M main
git push -u origin main
