# trance

**Human judgment, as an input.**

Trance is an open-source exploration of a desktop app that turns human reactions into context for AI agents.

It combines two live inputs:

- camera video and microphone audio
- screen video

The key technical bet is extracting gaze and facial micro-expression signals from the camera stream, grounding them in what is happening on screen, and using a multimodal model to steer an agent.

Trance keeps a short, continuously overwritten **hot timeline**, like a dashcam. The first version will activate manually. Eventually, a notable facial expression could activate Trance automatically and preserve the moments immediately before and after it.

The idea began with [this thesis](https://x.com/frvnkliu/status/2092215824404852944):

> I predict that when the last human frontier is good judgement the primary input will no longer be text nor voice. It will be distilled directly from our flesh.

The loop should remain visible, local-first, and controlled by the person being observed.

The initial target is macOS.

**Status:** early exploration; no working prototype yet.
