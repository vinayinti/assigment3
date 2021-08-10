#include <stdio.h>
enum day {sunday, monday, tuesday, wednesday, thursday, friday, saturday};
typedef enum day data;//here we aliasing the enum day as data
int main()
{
	data d = thursday;
	printf("The day number stored in d is %d", d);
	return 0;
}

