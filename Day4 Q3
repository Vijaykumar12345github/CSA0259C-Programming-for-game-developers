#include <stdio.h>
#include <stdlib.h>

typedef struct {
    char title[50];
    char author[50];
    float price;
} Book;

int main() {
	int i;
    Book books[5];
    for (i = 0; i < 5; i++) {
        printf("Enter the title of book %d: ", i+1);
        fgets(books[i].title, 50, stdin);
        printf("Enter the author of book %d: ", i+1);
        fgets(books[i].author, 50, stdin);
        printf("Enter the price of book %d: ", i+1);
        scanf("%f", &books[i].price);
        getchar();
    }
    for (i = 0; i < 5; i++) {
        printf("Book %d\n", i+1);
        printf("Title: %s", books[i].title);
        printf("Author: %s", books[i].author);
        printf("Price: $%.2f\n", books[i].price);
    }

    return 0;
}
