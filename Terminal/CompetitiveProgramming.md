Codeforces terminal tool - https://codeforces.com/blog/entry/66552 

## Debugging
- cout to see variables
- cerr to use a whole different stream
- macro:
    #define dbg(v)
      cout << "Line(" << __LINE__ << ") -> " << #v << " = " << (v) << endl;
- asserts to make sure a variable has the value it should: assert(false)
- #define NDEBUG to turn off asserts

## Tips
- using ll = long long;
- #define f first
- #define s second
