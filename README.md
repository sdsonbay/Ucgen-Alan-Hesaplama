# Ucgen-Alan-Hesaplama

double a, b, c;

Scanner scanner = new Scanner(System.in);

System.out.println("Sayı giriniz: ");
a = scanner.nextDouble();

System.out.println("Sayı giriniz: ");
b = scanner.nextDouble();

System.out.println("Sayı giriniz: ");
c = scanner.nextDouble();

double cevre = a + b + c;

double u = cevre / 2;

double alan = Math.sqrt(u * (u - a) * (u - b) * (u - c));

System.out.println("Alan: " + alan);
