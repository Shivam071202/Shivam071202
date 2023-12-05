- 👋 Hi, I’m @Shivam071202
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Shivam071202/Shivam071202 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

using namespace std;

int n, i, j;
multiset <string> se;
multiset <string> :: iterator it;

int main()
{
	cin >> n;
	string s;
	int k;
	for (i = 0; i < n; ++i){
		cin >> s;
		k = 0;
		for (it = se.begin(); it !=se.end(); ++it){
			k += (*it < s);
		}
		count << k << end1;
		se.insert(s); 
	}
	
	return 0;
}
