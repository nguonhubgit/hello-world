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


//2.3
		System.out.println("2.3");
		System.out.println("Enter a value for feet: ");
		double feet = input.nextDouble();
		double feetToMeter = feet * 0.305; 
		System.out.println(feet + " feet is " + feetToMeter + " meters.");

		System.out.println();

		//Converting meters to feet
		System.out.println("Enter a value for meter: ");
		double meter = input.nextDouble();
		double meterToFeet = meter * 1.0 / 0.305;
		System.out.println(meter + " meter is " + meterToFeet + " feets.");

		System.out.println();
		
