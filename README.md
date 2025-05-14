<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beautiful README.md</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #6b73ff 0%, #000dff 100%);
        }
        .shadow-soft {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.02);
        }
        .markdown-body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
        }
        .markdown-body h1, .markdown-body h2, .markdown-body h3 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
            margin-bottom: 16px;
        }
        .markdown-body code {
            background-color: rgba(27, 31, 35, 0.05);
            border-radius: 3px;
            padding: 0.2em 0.4em;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
        }
        .markdown-body pre {
            background-color: #f6f8fa;
            border-radius: 3px;
            padding: 16px;
            overflow: auto;
        }
    </style>
</head>
<body class="bg-gray-50 min-h-screen">
    <div class="container mx-auto px-4 py-12 max-w-4xl">
        <!-- Header -->
        <div class="gradient-bg text-white rounded-xl p-8 mb-8 shadow-soft hover-scale">
            <div class="flex items-center justify-between">
                <div>
                    <h1 class="text-4xl font-bold mb-2">Project Name</h1>
                    <p class="text-xl opacity-90">A brief and catchy description of your project</p>
                </div>
                <div class="bg-white p-3 rounded-full shadow-lg">
                    <i class="fas fa-rocket text-4xl text-blue-600"></i>
                </div>
            </div>
        </div>

        <!-- Badges -->
        <div class="flex flex-wrap gap-2 mb-8">
            <span class="bg-blue-100 text-blue-800 text-sm font-medium px-3 py-1 rounded-full flex items-center">
                <i class="fas fa-star mr-1"></i> Awesome
            </span>
            <span class="bg-green-100 text-green-800 text-sm font-medium px-3 py-1 rounded-full flex items-center">
                <i class="fas fa-code-branch mr-1"></i> Open Source
            </span>
            <span class="bg-purple-100 text-purple-800 text-sm font-medium px-3 py-1 rounded-full flex items-center">
                <i class="fas fa-bolt mr-1"></i> Fast
            </span>
            <span class="bg-yellow-100 text-yellow-800 text-sm font-medium px-3 py-1 rounded-full flex items-center">
                <i class="fas fa-shield-alt mr-1"></i> Secure
            </span>
        </div>

        <!-- Main Content -->
        <div class="markdown-body bg-white rounded-xl p-8 shadow-soft">
            <!-- Table of Contents -->
            <div class="bg-gray-50 p-4 rounded-lg mb-8">
                <h2 class="text-xl font-semibold mb-3 flex items-center">
                    <i class="fas fa-list-ul mr-2 text-blue-600"></i> Table of Contents
                </h2>
                <ul class="space-y-2">
                    <li><a href="#features" class="text-blue-600 hover:underline">✨ Features</a></li>
                    <li><a href="#installation" class="text-blue-600 hover:underline">🚀 Installation</a></li>
                    <li><a href="#usage" class="text-blue-600 hover:underline">📖 Usage</a></li>
                    <li><a href="#contributing" class="text-blue-600 hover:underline">🤝 Contributing</a></li>
                    <li><a href="#license" class="text-blue-600 hover:underline">📜 License</a></li>
                </ul>
            </div>

            <!-- Features -->
            <section id="features" class="mb-8">
                <h2 class="text-2xl font-bold flex items-center">
                    <i class="fas fa-sparkles mr-2 text-yellow-500"></i> Features
                </h2>
                <div class="grid md:grid-cols-2 gap-4 mt-4">
                    <div class="bg-gray-50 p-4 rounded-lg border-l-4 border-blue-500">
                        <h3 class="font-semibold text-lg mb-2">Feature One</h3>
                        <p class="text-gray-600">Detailed description of this amazing feature and what it does.</p>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-lg border-l-4 border-green-500">
                        <h3 class="font-semibold text-lg mb-2">Feature Two</h3>
                        <p class="text-gray-600">Detailed description of this amazing feature and what it does.</p>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-lg border-l-4 border-purple-500">
                        <h3 class="font-semibold text-lg mb-2">Feature Three</h3>
                        <p class="text-gray-600">Detailed description of this amazing feature and what it does.</p>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-lg border-l-4 border-red-500">
                        <h3 class="font-semibold text-lg mb-2">Feature Four</h3>
                        <p class="text-gray-600">Detailed description of this amazing feature and what it does.</p>
                    </div>
                </div>
            </section>

            <!-- Installation -->
            <section id="installation" class="mb-8">
                <h2 class="text-2xl font-bold flex items-center">
                    <i class="fas fa-rocket mr-2 text-purple-500"></i> Installation
                </h2>
                <p class="mt-2">Get started with our project in just a few simple steps:</p>
                
                <div class="mt-4 bg-gray-800 text-gray-100 p-4 rounded-lg overflow-x-auto">
                    <pre><code class="language-bash"># Clone the repository
git clone https://github.com/yourusername/yourproject.git

# Navigate to the project directory
cd yourproject

# Install dependencies
npm install

# Start the development server
npm start</code></pre>
                </div>
            </section>

            <!-- Usage -->
            <section id="usage" class="mb-8">
                <h2 class="text-2xl font-bold flex items-center">
                    <i class="fas fa-book-open mr-2 text-green-500"></i> Usage
                </h2>
                <p class="mt-2">Here's how to use our project effectively:</p>
                
                <div class="mt-4 bg-gray-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-lg mb-2">Basic Example</h3>
                    <div class="bg-gray-800 text-gray-100 p-4 rounded-lg overflow-x-auto">
                        <pre><code class="language-javascript">// Import the necessary module
const yourModule = require('yourmodule');

// Initialize with options
const instance = new yourModule({
    option1: true,
    option2: 'value'
});

// Use the module
instance.doSomethingAwesome();</code></pre>
                    </div>
                </div>
            </section>

            <!-- Contributing -->
            <section id="contributing" class="mb-8">
                <h2 class="text-2xl font-bold flex items-center">
                    <i class="fas fa-hands-helping mr-2 text-red-500"></i> Contributing
                </h2>
                <p class="mt-2">We welcome contributions from the community! Here's how you can help:</p>
                
                <div class="mt-4 space-y-4">
                    <div class="flex items-start">
                        <div class="bg-blue-100 p-2 rounded-full mr-3">
                            <i class="fas fa-code text-blue-600"></i>
                        </div>
                        <div>
                            <h3 class="font-semibold">Report Bugs</h3>
                            <p class="text-gray-600">Submit bug reports and feature requests through our issue tracker.</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="bg-green-100 p-2 rounded-full mr-3">
                            <i class="fas fa-code-branch text-green-600"></i>
                        </div>
                        <div>
                            <h3 class="font-semibold">Submit Pull Requests</h3>
                            <p class="text-gray-600">Fork the repository and submit pull requests with your improvements.</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="bg-purple-100 p-2 rounded-full mr-3">
                            <i class="fas fa-book text-purple-600"></i>
                        </div>
                        <div>
                            <h3 class="font-semibold">Improve Documentation</h3>
                            <p class="text-gray-600">Help us make the documentation clearer and more comprehensive.</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- License -->
            <section id="license">
                <h2 class="text-2xl font-bold flex items-center">
                    <i class="fas fa-balance-scale mr-2 text-gray-500"></i> License
                </h2>
                <div class="mt-4 bg-gray-50 p-4 rounded-lg">
                    <p>This project is licensed under the <strong>MIT License</strong> - see the <a href="LICENSE" class="text-blue-600 hover:underline">LICENSE</a> file for details.</p>
                </div>
            </section>
        </div>

        <!-- Footer -->
        <div class="mt-8 text-center text-gray-500">
            <p>Made with <i class="fas fa-heart text-red-500"></i> by Your Name</p>
            <div class="flex justify-center space-x-4 mt-2">
                <a href="#" class="text-gray-500 hover:text-blue-600"><i class="fab fa-github text-xl"></i></a>
                <a href="#" class="text-gray-500 hover:text-blue-400"><i class="fab fa-twitter text-xl"></i></a>
                <a href="#" class="text-gray-500 hover:text-red-500"><i class="fab fa-youtube text-xl"></i></a>
                <a href="#" class="text-gray-500 hover:text-purple-600"><i class="fab fa-discord text-xl"></i></a>
            </div>
        </div>
    </div>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Copy code blocks to clipboard
        document.querySelectorAll('pre code').forEach(codeBlock => {
            const copyButton = document.createElement('button');
            copyButton.className = 'absolute top-2 right-2 bg-gray-700 text-white px-2 py-1 rounded text-xs';
            copyButton.innerHTML = '<i class="fas fa-copy mr-1"></i> Copy';
            
            const pre = codeBlock.parentElement;
            pre.style.position = 'relative';
            pre.appendChild(copyButton);
            
            copyButton.addEventListener('click', () => {
                navigator.clipboard.writeText(codeBlock.textContent).then(() => {
                    copyButton.innerHTML = '<i class="fas fa-check mr-1"></i> Copied!';
                    setTimeout(() => {
                        copyButton.innerHTML = '<i class="fas fa-copy mr-1"></i> Copy';
                    }, 2000);
                });
            });
        });
    </script>
</body>
</html>
