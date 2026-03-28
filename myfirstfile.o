#include <stdio.h>
#include <string.h>

int main() {
    char file1[100], file2[100], file3[100];
    char searchTerm[50];

    printf("Enter first file name: ");
    scanf("%s", file1);

    printf("Enter second file name: ");
    scanf("%s", file2);

    printf("Enter third file name: ");
    scanf("%s", file3);

    printf("Enter search word: ");
    scanf("%s", searchTerm);

    printf("\nSearch Results:\n");

    if (strstr(file1, searchTerm)) {
        printf("%s -> Match found!\n", file1);
    } else {
        printf("%s -> No match found.\n", file1);
    }

    if (strstr(file2, searchTerm)) {
        printf("%s -> Match found!\n", file2);
    } else {
        printf("%s -> No match found.\n", file2);
    }

    if (strstr(file3, searchTerm)) {
        printf("%s -> Match found!\n", file3);
    } else {
        printf("%s -> No match found.\n", file3);
    }

    return 0;
}
