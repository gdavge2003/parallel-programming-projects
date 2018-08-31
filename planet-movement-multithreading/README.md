N-body Problem - Coarse vs. Fine and Satic vs. Dynamic

This program simulates the movement of 100 planets as they are affecting each other through their gravitational pulls. For each planet, their location on a 3D euclidean space is calculated by iterating through each other planet and considering the gravitational pull from each of those planets. This is done for each planet, and done 200 times to simulate a short view of how the planets move within those 200 “frames”. Through this program, we put in parallelism and take advantage of multi-threading at different loops with different thread allocation algorithms, and see the performance boost for each type.