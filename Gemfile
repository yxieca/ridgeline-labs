source "https://rubygems.org"

# Pin Jekyll to the version GitHub Pages uses, so local builds match
# what gets deployed.
# See https://pages.github.com/versions/ for the current pinned version.
gem "jekyll", "~> 3.10"

# Needed because _config.yml sets `kramdown.input: GFM` (GitHub-Flavored
# Markdown). On the GH Pages runtime this comes via the github-pages
# metagem, but for our standalone Jekyll build we list it explicitly.
gem "kramdown-parser-gfm", "~> 1.1"

group :jekyll_plugins do
  # No plugins yet — add here if needed (must be on the GH Pages allowlist).
end
