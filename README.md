# Maruthi
Pytgcall
from pytgcalls import PyTgCalls
from pytgcalls import idle
from pytgcalls.types import MediaStream
...
chat_id = -1001185324811
app = PyTgCalls(client)
app.start()
app.play(
    chat_id,
    MediaStream(
        'http://docs.evostream.com/sample_content/assets/sintel1m720p.mp4',
    )
)
idle()
