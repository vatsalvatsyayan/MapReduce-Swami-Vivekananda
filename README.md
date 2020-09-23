# MapReduce-Swami-Vivekananda
We will be analyzing the legendary speech that Swami Vivekananda gave on 11 September 1893 At the World’s Parliament of Religions, Chicago.
This speech shook the world, and we will be using MapReduce to find out the number of times a word was said.

To Run the program on the command line
1. Go to the folder directory in the command prompt
2. For running only map portion
    cat Swami Vivekananda’s Speeches at the World ‘s Parliament of Religions, Chicago, 1893.txt | python mapper.py
3. For running both map and reduce (the output of map would be input for reduce and only the reduce portion will be displayed)
     cat Swami Vivekananda’s Speeches at the World ‘s Parliament of Religions, Chicago, 1893.txt | python mapper.py | reducer.py
