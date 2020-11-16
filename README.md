To run the code:
Copy the three files (app.h, part1_udp.cc, and part2_buffsize.cc) from the sourceCode folder in the scratch folder of ns3.
Run the following command from just outside the scratch folde:

./waf --run scratch/part1_udp for part 1 
./waf --run scratch/part2_buffsize for part 2

It will generate .plt files for all the graphs on which the following command will give the corresponding .png file of the graph:
gnuplot <FileName>
