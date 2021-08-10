/*Write programs to understand the usage of below preprocessor directives.
#include, #if, #ifdef, #ifndef, #else, #elif, #endif, #define, #undef, #line, #error, and #pragma*/

#include<stdio.h>//include standard files to the program 
#define K 3//here defining k as 3
#ifndef Y//here checking Y is defined or not
    #define Y 6//here Y is defining because Y is defined before
#endif//This is end of the if condition
#undef Z//here Z is not defined or not checking
    #define Z 7


int main()
{
    int p=K,q,r;
    q=Y;r=Z;
    printf("%d %d %d ",p,q,r);
    return 0;
}
