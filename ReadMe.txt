A sample code that shows the difference between template vector, vector&lt;T&gt;, and the specialized vector for type bool, vector&lt;bool&gt;.

vector&lt;bool&gt; does not satisify the container requirements, e.g. X::reference requirement defined in Table 96 in 23.2.1 General container requirements in the C++ Standard 2011.

Also, it has performance issues comparing with vector&lt;T&gt; (This example show the results comparing with vector&lt;int&gt; and vector&lt;char&gt;).

vector&lt;bool&gt; is not as good as we expected at the first glance.
