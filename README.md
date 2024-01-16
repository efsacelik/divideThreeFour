# divideThreeFour
A program that calculates the average of numbers divisible by 3 and 4 from 0 to the entered number using Java loops.
Scanner input = new Scanner(System.in);
		
		System.out.print("Enter an integer:");
		int a = input.nextInt();
		
		int sum = 0;
		int adet = 0;
		for (int i = 1; i <= a; i++) {
			if (i % 12 == 0) {

				sum += i;
				adet += 1;

				// System.out.println(sum / adet) eğer buraya yazsaydık her 12ye bölünen için
				// ortalama yazardı.
			}

		}
		System.out.println(sum / adet);

	}

}
