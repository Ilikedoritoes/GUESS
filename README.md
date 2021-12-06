void main()
{
	int guess = 30;
	int what;
	int num;
		printf("guess what number i am thinking of!\n");

		for (num = 0;num < 10; num++)
		{
			scanf_s("%d", &what);
			num + 1;
			if (what > guess)
				printf("too big!");
			if (what < guess)
				printf("too small!");
			if (what == guess)
				printf("WOOOOwwww you did it.");
		}

		system("pause");
}

