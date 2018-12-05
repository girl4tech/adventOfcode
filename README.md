# Advent of Code Answers by Day - C#
These challenges were created by Eric Wastl: https://adventofcode.com/2018/about

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
            //C&P FREQUENCY INPUTS INTO THE LIST BELOW
            List<int> frequencyInputs = new List<int> {+1, +2, +3, +4, -5, -6, -7};
            {
                int finalFrequency = frequencyInputs.Sum();
                Debug.WriteLine(finalFrequency);
                //ANSWER: 538
            }

        }
    }
}
```

# Day2
