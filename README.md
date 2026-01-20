'''c
#include <stdio.h>

void name(const char *value)        { printf("Name: %s\n", value); }
void role(const char *value)        { printf("Role: %s\n", value); }
void languages(const char *value)   { printf("Languages: %s\n", value); }
void interests(const char *value)   { printf("Interests: %s\n", value); }

void profile(void) {
    name("Sebastian.");
    role("Amateur Coder.");
    languages("C");
    interests("open-source, data structures");
}
'''
