# Papur: The Free & Open RSS Feed Reader.

**co-owners:** [Cai Williams](https://github.com/mr-fish8) and [Morgan Jones](https://github.com/morganlabs)

Welcome to Papur! The free & open RSS feed reader.

**⚠️ THIS IS VERY EARLY, INCOMPLETE SOFTWARE. ⚠️**

---

## Plan

* Papur will be a locally-hosted RSS news feed reader, however the possibility for
Papur-hosted sync is not out of the question for the future. The primary sync
would be using a Git repository, if the user chooses to do so. Upon opening the
app, the app would grab the latest information from the repository and download
it to the device.
* Cache news from feeds **of the users choice**. When adding a new feed to Papur,
the user can choose whether or not to download cache of that feed every once in
a while. This means that the user can read these offline, whereas the rest 
require an internet connection.
* The application will be cross-platform. Cai will handle the Mobile application
using Flutter(?), and Morgan will handle the Desktop applications using Tauri and
Svelte. This allows us to create a cross-platform app with minimal need for 
maintainers on each individual platform.

## Featureset

* Add custom RSS feeds
* Custom word blocklist
* Locally hosted with optional Git repository sync
* Per-feed caching
* List of RSS feeds that users can quickly add (dependent on their location?)
* A bias slider (Needs research. ChatGPT? A pre-existing API? etc.)

## Stacks

### Desktop

* Rust + Tauri
* Svelte

### Mobile

<!-- To be filled in by Cai -->
