# PA Tuner recorder

A one-page browser recorder: mono, with echo cancellation, noise suppression and automatic gain requested off.
It saves a 32-bit float WAV and a JSON file of the settings the browser actually applied. Everything stays on the
device; the page loads nothing else and sends nothing anywhere.

Served here over HTTPS so a phone's browser will open the microphone.

It can be added to the home screen (Share, then Add to Home Screen) and opens offline once loaded. The page and
each capture's JSON record whether it was opened from the home screen or a browser tab.
