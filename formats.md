# fluidity. Templates Reference

## Comments

Regular comment:
```html
<h2 class="text-2xl">Name</h2>
<p>Details</p>
````

Artist/Owner comment (verified):

```html
<h2 class="text-2xl">Name &check;</h2>
<p>Details</p>
```

## Pending Artists

```html
<div class="bg-gray-500 p-4">
  <h2 class="text-3xl text-black">Pending Artists</h2>
  <img src="imageofartist.jpg" alt="Pending Artist" />
  <p>Artist Name</p>
</div>
```

## Artist Page Template

```html
<!doctype html>
<html>
<head>
    <title>fluidity. - The music label that simplifies everything.</title>
    <link rel="stylesheet" href="../../output.css" />
</head>
<body class="bg-gray-800">
    <!-- Header / Navigation -->
    <header class="bg-gray-500">
        <nav class="container mx-auto px-4 py-2 flex justify-between items-center">
            <h1 class="font-bold italic text-white">fluidity.</h1>
            <ul class="flex gap-4">
                <li><a href="../../index.html" class="text-white hover:text-gray-300">Home</a></li>
                <li><a href="../../about.html" class="text-white hover:text-gray-300">About</a></li>
                <li><a href="https://forms.gle/5BrV5aGtFkDjUzLUA" class="text-white hover:text-gray-300">Submit a demo</a></li>
            </ul>
        </nav>
    </header>

    <!-- Artist Info -->
    <main class="container mx-auto px-4 py-6">
        <div class="text-center">
            <h1 class="text-5xl text-cyan-400">Artist Name</h1>
            <p class="text-white">Joined on: Date joined</p>
        </div>

        <!-- New Songs Section -->
        <div class="bg-gray-500 p-4 mt-6">
            <h2 class="text-3xl text-black">New Songs</h2>
            <p>BEAUTIFUL EXPERIENCES</p>
            <p>[Platform Display]</p>
            <!-- Embed iFrame here -->
            IFrame link
        </div>
    </main>
</body>
</html>
```

## Symbols

* ✅ **Checkmark**: Verified (usually an artist or owner on fluidity.)

## Paths / Handles

* `artist/@artistname` → Represents the artist’s handle, e.g., `artist/@artistname`
