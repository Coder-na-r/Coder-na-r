```cpp

#include <map>
#include <vector>
#include <string>

using std::map, std::vector, std::string;

namespace VladosSizyh {

    class About : public Me
    {
        map<string, string> getCurrentWorkplace()
        {
            return {
                    { "company", "nullptr"},
                    { "university", "ISU (Irkutsk State University)" },
                    { "position", "student" }
            };
        }

        vector<string> getDailyKnowledge()
        {
            return {
                "C++",
                "Python",
                "Arduino C++",
                "Kotlin",
                "MySql"
            };
        }

        vector<string> usedTechnologies()
        {
            return {
                "internet of things (platforms -> esp8266, arduino)",
                "computer vision (cv2)",
                "machine learning (tensorflow)",
                "architecture, solid pritsnips, design patterns, etc."
            };
        }

        vector<string> futurePlans()
        {
            return {
                "deep learning asm and computere science"
            };
        }
    };
}
```