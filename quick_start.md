🚀 Quick Start
1. Install MCP-T
bashnpm install -g mcp-t-cli
# or
pip install mcpt
2. Generate Your First Server
bashmcpt generate "Stripe payment processor with fraud detection"
3. Deploy to Production
bashmcpt deploy --platform netlify
4. Use with Any Platform
javascript// Perfect for bolt.new, Replit, Cursor
const api = 'https://your-server.netlify.app'
const response = await fetch(`${api}/process_payment`, {
  method: 'POST',
  body: JSON.stringify({ amount: 1000, card: '...' })
