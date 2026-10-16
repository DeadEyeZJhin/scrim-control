# Scrim Control · Co-host

Button page for the co-hosts of the Core Runners scrim stream. Opens with a 6-digit PIN from the host.

The page holds no secrets: it only calls PIN-checked functions on Supabase; the PIN and the host PC token exist there only as bcrypt hashes.
