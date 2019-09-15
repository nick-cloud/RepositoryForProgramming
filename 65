#include <iostream>
#include <iomanip>
#include <string>
#include <map>
#include <random>
#include <cmath>
int main()
{
    int f;
    void Dowork(int a, int b);
f = [](int a)
{
    std::random_device rd;
    std::mt19937 gen(rd());

    std::normal_distribution<> d(5,2);

    std::map<int, int> hist;
    for(int n=0; n<20000; ++n) {
        ++hist[std::round(d(gen))];
    }
    for(auto p : hist) {
        std::cout << std::fixed << std::setprecision(1) << std::setw(2)
                  << p.first << ' ' << std::string(p.second/200, '*') << '\n';
    }
}
DoWork(int a, f);
return 0;
}
