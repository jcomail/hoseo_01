#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    srand(time(NULL));   // 현재 시간을 시드값으로 줌
    printf("%d\n", rand()); // 난수 출력
    return 0;
}
