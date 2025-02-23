# Код из 1 семестра
#include <iostream>
// #include <vector>

using namespace std;

int main()
    {
    int n, p;

    int res = 1;

    cin >> n >> p;

    for (int i = 0; i < p; i ++)
    {

        res *= n;
    }

    cout << res;

    return  0;
}
