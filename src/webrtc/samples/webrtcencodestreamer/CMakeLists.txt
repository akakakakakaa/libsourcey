include_dependency(WebRTC REQUIRED)
include_dependency(FFmpeg REQUIRED)

define_sourcey_module_sample(webrtcencodestreamer base crypto av net http util json socketio symple webrtc)
