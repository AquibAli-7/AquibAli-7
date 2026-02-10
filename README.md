# hi i m Aquib Ali

<!-- Container for code block + button -->
<div style="position: relative;">
  <!-- Copy button -->
  <button 
    style="position: absolute; top: 5px; right: 5px; z-index: 1;"
    onclick="navigator.clipboard.writeText(document.getElementById('my-code-snippet').textContent).then(() => this.textContent = 'Copied!').then(() => setTimeout(() => this.textContent = 'Copy', 2000))"
  >
    Copy
  </button>
 
  <!-- Code snippet (with id for targeting) -->
  <pre><code id="my-code-snippet">
# Example code snippet
print("Hello, World!")
for i in range(5):
    print(i)
  </code></pre>
</div>
