# Install

Galactic Survey NeoForge Edition installs through ECHO Launcher after verified
release artifacts exist.

The Launcher must resolve `moduleRequirements` from
`release-manifest.template.json`, download `-neoforge.jar` artifacts for the NeoForge
runtime target, verify SHA-256 checksums, and refuse public-alpha install when
runtime or gameplay evidence is missing.

Preview installs may use local artifacts, but they must stay outside the public
alpha channel.
