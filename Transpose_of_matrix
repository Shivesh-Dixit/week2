#include <iostream>
#include <bits/stdc++.h>
using namespace std;
int main()
{
    cout << "Enter the dimensions of the matrix : " << endl;
    int n, m;
    cin >> n >> m;
    vector<vector<int>> vt(n, vector<int>(m));
    cout << "Enter the matrix : " << endl;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < m; j++)
        {
            cin >> vt[i][j];
        }
    }
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < i; j++)
        {
            swap(vt[i][j], vt[j][i]);
        }
    }
    cout << "The transpose of the matrix is : " << endl;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < m; j++)
        {
            cout << vt[i][j] << " ";
        }
        cout << endl;
    }
    return 0;
}
