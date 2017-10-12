# hello-world
My first repository

I'm learning about github. It's cool :)

Changed: Adding line


int i, j, k;
		i = j = k = 2;
		System.out.println(i + " " + j + " " + k);

		System.out.println("25/4 is " + 25/4);

		System.out.println();

		//2.1 
		System.out.println("2.1");
		System.out.println("Enter a degree in Celsius: ");
		Scanner input = new Scanner(System.in);
		double celsius = input.nextDouble();
		double fahrenheit = 9.0 / 5.0 * celsius + 32.0;
		System.out.println(celsius + " Celsius is " + fahrenheit + " Fahrenheit.");

		System.out.println();

		//2.2
		System.out.println("2.2");
		System.out.println("Enter the radius and length of a cylinder: ");
		//Scanner input2 = new Scanner(System.in);
		double radius = input.nextDouble();
		double length = input.nextDouble();

		final double PI = 3.14159;
		double area = radius * radius * PI;
		double volume = area * length;

		System.out.println("The area is " + area + ".");
		System.out.println("The volume is " + volume + ".");
