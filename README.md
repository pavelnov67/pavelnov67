- 👋 Hi, I’m @pavelnov67
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
pavelnov67/pavelnov67 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->public class Quadratic_Equation {
    public static void main(String[] args) {
        System.out.println("hello let`s go");
        Scanner sc = new Scanner(System.in);
        System.out.println("Введите a:");

        double number_a = sc.nextInt();

        System.out.println("Вы ввели a= " + number_a);

        System.out.println("Введите b:");
        double number_b = sc.nextInt();
        System.out.println("Вы ввели b= " + number_b);

        System.out.println("Введите c:");
        double number_c = sc.nextInt();
        System.out.println("Вы ввели b= " + number_c);

        double a = number_a;
        double b = number_b;
        double c = number_c;

        double d = b * b - 4 * a * c;
        System.out.println("discriminant= " + d);
        double x_1 = (-b - Math.sqrt(d)) / 2 * a;
        double x_2 = (-b + Math.sqrt(d)) / 2 * a;
        double x_3 = (-b) / 2 * a;

        if (d >= 0) {
            System.out.println("X1= " + x_1);
            System.out.println("X2= "+x_2);
        }    else {
            System.out.println("X= "+x_3);
        }


    }
}
