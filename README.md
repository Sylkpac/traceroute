# Trace the Route!  

### Understanding the Journey

Imagine sending a message to a friend online. That message travels as a packet of data, hopping across different networks and routers to reach its destination. Tracing this journey is crucial for:

* **Diagnosing Network Issues:** Identify bottlenecks or delays causing slow connections.
* **Understanding Internet Routing:** See the complex web of networks packets traverse.
* **Optimizing Network Performance:** Gain insights for improving network efficiency.

## Let's Get Tracing!
This exercise will guide you through using _**traceroute**_ on Linux/macOS or _**tracert**_ on Windows to visualize the path your data takes.

### What You'll Learn:
Trace the route packets take to reach a specific website.
Gain insights into the complexity and structure of internet routing.

### Preparation:
* **Linux/macOS:** Most systems already have traceroute pre-installed.
* **Windows:** Use the built-in command tracert.

## Tasks:

**A. Trace It!**
1. Open Terminal (Linux/macOS) or Command Prompt (Windows).
2. Run the Command:   
    **Linux/macOS:** Type _**traceroute google.com**_ and press _**Enter**_
    **Windows:** Type _**tracert google.com**_ and press _**Enter**_

**B. Decoding the Results:**

The output shows a list of "hops," each representing a router or gateway the data packet encounters.

Here's what you'll typically see for each hop:
* **Hop Number:** The order in which the packet reaches that point.
* **IP Address:** The unique identifier of the router.
* **Round-Trip Time** (RTT): The time (usually in milliseconds) it takes for a packet to reach that hop and return. It might be displayed three times for accuracy.

### What You'll Gain:

* **Internet Routing Complexity:** See how packets travel through multiple networks.
* **Network Performance:** Analyze RTTs to understand latency between your computer and each hop.
* **Troubleshooting Skills:** Identify potential bottlenecks or delays that might affect your connection.

