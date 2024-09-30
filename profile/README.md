# Paper
- "RISOPA: Rapid Imperceptible Strong One-Pixel Attacks in Deep Neural Networks"  
- 📜 https://www.mdpi.com/2227-7390/12/7/1083
- Indexed in Scopus
- 🏆 Best Paper Award at the Korean Conference on Computer Science (July 2024)

# Summary 

In recent years, artificial intelligence has been developing with achievements in
various fields such as image recognition and natural language processing. In
particular, most of them show a level that exceeds human cognitive ability, and
malicious attacks on artificial intelligence are also evolving and diversifying.
According to related studies, it has been found that artificial intelligence can
malfunction with only a slight change in the input image. In particular, various
studies have been conducted on an attack method that induces false recognition
of artificial intelligence by transforming only the color value of a single pixel.
In a single pixel attack, the coordinates of the pixel to be changed and the color
value of the pixel must be specified. Existing studies specify pixel coordinates and
color values using a differential-evolution algorithm. The differential evolution
algorithm is a heuristic algorithm that finds better values through random search
through many computational processes. The differential evolution algorithm
used in existing studies has the disadvantage of not finding the optimal answer
or wasting search time when the number of repetitions is small. However, due to
the nature of the algorithm, it takes a lot of time and does not provide consistent
results.
To solve this problem, this study proposes a gradient-based search algorithm
that introduces the concept of momentum. The proposed algorithm selects
candidates of pixels to attack in advance in order to perform an optimal attack
and defines the change in confidence according to the change in color value as
the slope carries out the loop. To perform a more efficient single pixel attack, we
propose a gradient search algorithm that introduces the concept of momentum.
The algorithm proposed in this project shows 1) an efficient confidence score of
the neural network for the image, 2) an attack with a modified minimum color
value 3) an attack that proceeds fast in time.

# Demo
https://github.com/Konkuk-fvlab/demo-repository


