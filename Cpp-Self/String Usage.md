# String Usage

## initialization

`string s1`

`string s2 = s1`

`string s3 = "Hello"`

`string s4(10,'c')`  s4 = "cccccccccc"





## Read in

string word;

cin >> word ; // read in a word, no white space

getline(cin, word); // read in a line, with white space.



## Other Operations

string line;

line.size();  //return an unsigned int

line = line1; //replace contents of line with a copy of line1

line+=line2;



## Access Single Characters

like an array: s[0],s[1],s[2],....,s[s.size()-1]

