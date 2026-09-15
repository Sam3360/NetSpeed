# NetSpeed

A lightweight, ad-free internet speed test built as a Progressive Web App (PWA).

NetSpeed measures **ping, download speed, and upload speed** directly from the browser, with a simple real-time speed gauge.

## Features

* Ping, download, and upload speed tests
* Real-time speed gauge
* Installable as a PWA
* Offline caching
* Responsive design
* No ads or backend required
* Works with static hosting such as GitHub Pages

## Tech Stack

* HTML
* CSS
* Vanilla JavaScript
* Fetch API
* Streams API
* Performance API
* Service Workers

## How It Works

NetSpeed uses browser APIs to measure how quickly data can be transferred between the user and the test source.

Results are shown in:

```text
Ping:       ms
Download:   Mbps
Upload:     Mbps
```

Actual results can vary depending on the network, device, browser, and test server.

## Running Locally

```bash
git clone https://github.com/Sam3360/netspeed.git
cd NetSpeed
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

NetSpeed can be deployed directly to GitHub Pages or any other static hosting service. No server or database is required.

## License

MIT License
