#include <stdio.h> 
int dfs(int n) {
    return n == 1 ? 10 : dfs(n - 1) + 2;
}
int main() 
{
    
    printf("第5个人的年龄是%d岁", dfs(5)); 
    return 0;
} 
