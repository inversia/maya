# <a href="https://xpl.github.io/what-code-is-faster/">What Code Is Faster?</a>

**A browser-based tool for speedy and correct JS performance comparisons!**

- Minimalistic UI
- Code editor with IntelliSense
- All state is saved to URL - copy it and share with friends in no time!
- Automatically determines the number of iterations needed for a proper measurement — no hard-coding!
- Prevents dead code elimination and compile-time evaluation optimizations from happening (those can ruin your test!)
- Verifies code correctness (functions must compute the same value, be deterministic, depend on their inputs, etc.)

<a href="https://xpl.github.io/what-code-is-faster/"><img width="100%" alt="Try it online!" src="https://user-images.githubusercontent.com/1707/101344538-af2ace00-3896-11eb-808c-824a228dc50f.png"></a>

## Examples

- <a href="https://xpl.github.io/what-code-is-faster/?code=eNq1jbEKwjAURfd%2BxV2kSY1CZxEHQXBw1fmljSRok5q8CiL9d0sr0h9wucM9792jja9sQ%2FEm8oslxj7UBseEAyU2cZcrXDtfsQsezjt2dD%2FTvTNC4p0B0XAXPU7Edh3J16ERMuvVyOyrDSzaaJ7TLVAFnxiELcYaS5QSC5QzqH9wNYdzz7RLClpuBtirIdIj%2FkM1zlJBw7suvrqsl9kHf%2BtYAA%3D%3D">Math.hypot or Math.sqrt?</a>
- <a href="https://xpl.github.io/what-code-is-faster/?code=eNqVjz0OwjAMhfecwgtqIiokTsCC2FjZTZrSiNRB%2BUFFKHcnSaVCR5Yo9nvPn91HkkFbgj4SnwS8wakQHcEZw7Dzuja3cyWtL1Vi7KpIDiO6O2%2BOFoyVaMqAeVKnpEGH5e8hZwIgvcKg6XZo2q9Nkw4azQVNVDyDGazQDqmzIxcstVVTU1CO0PCHU8%2FZvgTK7qUNG9iLLKQ2P3WrlXtBV%2Bn0x8E%2FrCW7ArIk2AdkO2vC">Do local function declarations affect performance?</a>
- <a href="https://xpl.github.io/what-code-is-faster/?code=eNqNj70OwjAMhPc8hRfURFRIzAixIDZW9hBSGpE6yElQEcq7k7Si%2FEwsluw732c3EVUwDqGJyHsBDyAdIiHsZWgX3gzD%2Bdgp50uXGDtqVG0n6cKrrQNlnY%2BkPWRDAIn30Bo8b6q6hI7pBk0w0h6kjZpnCoMvDkk8uY4LlupB033QhNLyK%2BnbaJ8WyqFlDDNYiiykOhfr1I97Qg%2FSLi%2BV55TDfGIPa3hFrP55%2BAP%2FjitslgR7AtISZ6c%3D">Do closures affect performance (vs. free functions)?</a>
- <i>..Add your own? Pull Requests are welcome!</i>
