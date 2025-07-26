#include <iostream>
using namespace std;

int main() {
    int plotWidth = 150;
    int plotHeight = 150;
    int roadWidth = 14;

    int cols = 3;
    int rows = 3;

    long int totalWidth = (plotWidth * cols) + (roadWidth * (cols + 1));
    long int totalHeight = (plotHeight * rows) + (roadWidth * (rows + 1));

    long int totalArea = totalWidth * totalHeight;
    int plotArea = (plotWidth * plotHeight) * (cols * rows);
    int roadArea = totalArea - plotArea;
  
    cout << "square area: " << plotArea << " blocks" << endl;

if (plotArea > 22500) {
  cout << "qualified as mega-plot" << endl;
if (plotArea > 200000) {
  cout << "avg megaplot"; 
 }
}
return 0;

}
