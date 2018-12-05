# adventOfcode Answers by Day (C#)

# Day 1
```using System;
using System.Diagnostics;
using System.Collections.Generic;
using System.Linq;

namespace AdventOfCode
{
    class FrequencyDetection
    {
        static void Main(string[] args)
        {   
            //copy and paste frequency inputs to the list below
            List<int> frequencyInputs = new List<int> {+1, +2, +3, +4, -5, -6, -7};
            {
                int finalFrequency = frequencyInputs.Sum();
                Debug.WriteLine(finalFrequency);
                //answer: 538
            }

        }
    }
}```

# Day2
