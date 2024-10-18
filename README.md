# Awesome WebRTC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> WebRTC is real-time communication for the web.

Community list of awesome WebRTC projects, apps, tools, libraries and more.

## Contents

- [Official](#official)
- [Samples](#samples)
- [Libraries](#libraries)
	- [JavaScript](#javascript)
	- [Node](#node)
	- [Go](#go)
	- [C/C++](#cc)
- [Stun & Turn](#stun--turn)
- [Projects](#projects)
	- [Audio](#audio)
	- [Chat](#chat)
	- [File Transfer](#file-transfer)
	- [Game](#game)
	- [Screen](#screen)
	- [Server](#server)
	- [Streaming](#streaming)
	- [Video Conference](#video-conference)
	- [Tool](#tool)
- [Miscellaneous](#miscellaneous)
- [Contribute](#contribute)

## Official

- [Website](https://webrtc.org/) - Official WebRTC website.
- [MDN](https://developer.mozilla.org/en-US/docs/Glossary/WebRTC) - WebRTC on MDN web docs.
- [Source](https://webrtc.googlesource.com/src) - WebRTC source repository.
- [Live demos](https://webrtc.github.io/samples/) - WebRTC Live demos.

## Samples

- [androidwebrtcexample](https://github.com/agent10/androidwebrtcexample) - WebRTC Android example.
- [Cube Slam by Google](https://experiments.withgoogle.com/cube-slam) - Cube Slam is a video game that you can play face-to-face against your friends.
- [Electron Screen Recorder](https://github.com/hokein/electron-screen-recorder) - A WebRTC screen recorder electron application.
- [go-video-conference](https://github.com/Ramez-/go-video-conference) - Create a video conference using Golang.
- [Heyy-chat-app](https://github.com/IshuPrabhakar/Heyy-chat-app) - A Realtime Chat Application using flutter, Asp.Net Core Web Api, SignalR , WebRTC etc.
- [media-server-go-demo](https://github.com/notedit/media-server-go-demo) - Webrtc media server go demo.
- [p2p-chat](https://github.com/michal-wrzosek/p2p-chat) - Serverless peer to peer chat on WebRTC.
- [Peer-to-Peer Cue System](https://github.com/jmcker/Peer-to-Peer-Cue-System) - Cue system for simple two-way communication and visual signaling using a PeerJS peer-to-peer connection.
- [Peertransfer](https://github.com/perguth/peertransfer) - Send a file p2p and e2e encrypted in your browser using WebRTC.
- [react-webrtc](https://github.com/diegogurgel/react-webrtc) - Video chat using webRTC and react.
- [React Native webRTCApp](https://github.com/delta4infotech/React-native-webrtcApp) - React native webrtc app demo.
- [Realtime Chat Application](https://github.com/adrianhajdin/project_video_chat) - React Video Chat Application using WebRTC.
- [Record Audio-Videos](https://github.com/GersonRosales/Record-Audios-and-Videos-with-getUserMedia) - Examples to record using getUserMedia.
- [serverless-webrtc](https://github.com/svarunan/serverless-webrtc) - Webrtc p2p without signalling server.
- [Simple WebRTC Signaling Server](https://github.com/aljanabim/simple_webrtc_signaling_server?tab=readme-ov-file#simple-webrtc-signaling-server) - A WebRTC signaling server implemented in Node.js with Socket.io.
- [stream-live-system](https://github.com/nelsonwenner/stream-live-system) - An example of a live broadcast system using microservice concepts and architected with docker.
- [transparent-virtual-background](https://github.com/webrtcHacks/transparent-virtual-background) - Transparent backgrounds with WebRTC.
- [Video-Call-App](https://github.com/amirsanni/Video-Call-App) - A text, audio and video chat application built with webRTC and Ratchet (PHP WebSocket).
- [Video-Call-App-Node.js](https://github.com/amirsanni/Video-Call-App-Node.js) - A conference call implementation using WebRTC, Socket.io and Node.js.
- [Video Chat](https://github.com/mihir0699/Video-Chat) - Video calling and chatting app (PWA) built using React.js, Web RTC and Socket.io.
- [video-chat](https://github.com/Fernanda-Kipper/video-chat) - This application is a video-chat built using WebRTC and P2P Connections where you can call and talk to all online users.
- [Video Chat WebApp](https://github.com/sastava007/Video-Chat-WebApp-Scalled-Horizontally) - Video Chat WebApp using Node.js | Redis | VueJS | WebRTC | Socket.io.
- [Video Meeting](https://github.com/0x5eba/Video-Meeting) - Google Meet / Zoom clone in a few lines of code.
- [video-group-meeting](https://github.com/Hyunse/video-group-meeting) - WebRTC video chat for multi users using React and Node Express.
- [videosdk-rtc-react-sdk-example](https://github.com/videosdk-live/videosdk-rtc-react-sdk-example) - WebRTC based video conferencing SDK for React JS.
- [Video-conferencing-web-application](https://github.com/omkar13/Video-conferencing-web-application) - Developed a multi-party video conferencing and web chat application using WebRTC, JavaScript and Web-sockets with features such as canvas sharing, presentation sharing and video sharing.
- [webrtc](https://github.com/maitrungduc1410/webrtc) - Mirror of The Official WebRTC repository.
- [webrtc-video-conference-simple-peer](https://github.com/Dirvann/webrtc-video-conference-simple-peer) - A simple video conferencing example using simple-peer.
- [webrtc-cpp-sample](https://github.com/llamerada-jp/webrtc-cpp-sample) - Sample program for using WebRTC on C++.
- [WebRTC Code Samples](https://github.com/webrtc/samples) - WebRTC Web demos and samples.
- [webrtc-data-channel-demo](https://github.com/TomasHubelbauer/webrtc-data-channel-demo) - WebRTC Data Channel demo.
- [WebRTC Experiment](https://github.com/muaz-khan/WebRTC-Experiment) - WebRTC, WebRTC and WebRTC. Everything here is all about WebRTC.
- [webrtc-examples](https://github.com/WowzaMediaSystems/webrtc-examples) - WebRTC Examples.
- [webrtc-sample](https://github.com/Swizec/webrtc-sample) - Demo app to learn WebRTC. Communicates with itself via RTCPeerConnection.
- [WebRTC Video/Audio Broadcast](https://github.com/TannerGabriel/WebRTC-Video-Broadcast) - WebRTC video/audio broadcast.
- [WebRTC Video Conference](https://github.com/avoup/webrtc-video-conference) - WebRTC video conference app.
- [Yew-WebRTC-Chat](https://github.com/codec-abc/Yew-WebRTC-Chat) - A simple WebRTC chat made with Yew.

## Libraries

### JavaScript

- [adapter.js](https://github.com/webrtcHacks/adapter) - JavaScript shim for abstracting WebRTC spec changes and inconsistencies.
- [data-transport](https://github.com/unadlib/data-transport) - A simple and responsible universal transport.
- [DetectRTC](https://github.com/muaz-khan/DetectRTC) - A tiny JavaScript library that can be used to detect WebRTC features e.g. system having speakers, microphone or webcam, screen capturing is supported, number of audio/video devices etc.
- [discovery-swarm-webrtc](https://github.com/geut/discovery-swarm-webrtc) - Discovery-swarm for WebRTC.
- [hyperhost](https://github.com/t-mullen/hyperhost) - P2P Node Servers in the Browser.
- [instacam](https://github.com/xavierfoucrier/instacam) - Library to perform instant canvas video through the WebRTC API with a fresh touch of CSS filters.
- [liowebrtc](https://github.com/lazorfuzz/liowebrtc) - An event-based WebRTC library that makes it easy to embed real-time peer to peer communication into UI components.
- [LiveKit browser client SDK](https://github.com/livekit/client-sdk-js) -  Add real-time video, audio and data features to your JavaScript/TypeScript app.
- [MediaStreamRecorder](https://github.com/streamproc/MediaStreamRecorder) - Cross browser audio/video/screen recording.
- [MultiStreamsMixer](https://github.com/muaz-khan/MultiStreamsMixer) - JavaScript library that allows you pass multiple streams (e.g. screen+camera or multiple-cameras) and get single stream.
- [NetplayJS](https://github.com/rameshvarun/netplayjs) - Make P2P multiplayer browser games, no server hosting or synchronization code required, powered by rollback netcode + WebRTC.
- [P2P Media Loader](https://github.com/Novage/p2p-media-loader) - An open-source engine for P2P streaming of live and on demand video directly in a web browser HTML page.
- [PeerLite](https://github.com/skyllo/peer-lite) - Lightweight WebRTC browser library that supports video, audio and data channels.
- [peerjs](https://github.com/peers/peerjs) - Simple peer-to-peer with WebRTC.
- [peerfetch](https://github.com/ambianic/peerfetch) - Peer-to-peer HTTP over WebRTC.
- [RTCMultiConnection](https://github.com/muaz-khan/RTCMultiConnection) - WebRTC JavaScript library for peer-to-peer applications (screen sharing, audio/video conferencing, file sharing, media streaming etc).
- [RecordRTC](https://github.com/muaz-khan/RecordRTC) - WebRTC JavaScript library for audio/video as well as screen activity recording.
- [simple-peer](https://github.com/feross/simple-peer) - Simple WebRTC video, voice, and data channels.
- [simple-peer-files](https://github.com/subins2000/simple-peer-files) - A library to send files over WebRTC.
- [trystero](https://github.com/dmotz/trystero) - Build instant multiplayer webapps, no server required.
- [video-stream-merger](https://github.com/t-mullen/video-stream-merger) - Merge multiple video MediaStreams into one composite.
- [webConnect.js](https://github.com/nuzulul/webConnect.js) - Auto WebRTC peer-to-peer connection for static client side web application.
- [WebPEER](https://github.com/nuzulul/webpeerjs) - WebPEER is a novel decentralized P2P network inside browser with a chance of working.
- [WebRTCStats](https://github.com/peermetrics/webrtc-stats) - Helps you collect stats for peer connections.
- [webrtc-issue-detector](https://github.com/VLprojects/webrtc-issue-detector) - Diagnostic tool and troubleshooter for WebRTC applications with Mean Opinion Score (MOS) calculator.
- [WebTorrent](https://github.com/webtorrent/webtorrent) - Streaming torrent client for the web.

### Node

- [mediasoup](https://github.com/versatica/mediasoup/) - Cutting Edge WebRTC Video Conferencing.
- [medooze-media-server](https://github.com/medooze/media-server-node) - WebRTC Media Server for Node.js.
- [node-datachannel](https://github.com/murat-dogan/node-datachannel) - Easy to use WebRTC data channels and media transport. libdatachannel node bindings.
- [node-webrtc](https://github.com/node-webrtc/node-webrtc) - Node.js Native Addon that provides bindings to WebRTC.
- [SIP.js](https://github.com/onsip/SIP.js) - A simple, intuitive, and powerful JavaScript signaling library.
- [simple-signal](https://github.com/t-mullen/simple-signal) - Signalling solution for simple-peer with socket.io.
- [werift-webrtc](https://github.com/shinyoshiaki/werift-webrtc) - WebRTC Implementation for TypeScript (Node.js), includes ICE/DTLS/SCTP/RTP/SRTP/WEBM/MP4.

### Go

- [flutter-webrtc-server](https://github.com/flutter-webrtc/flutter-webrtc-server) - A simple WebRTC signaling server for flutter-webrtc.
- [Kraken](https://github.com/MixinNetwork/kraken) - High performance WebRTC SFU implemented with pure Go.
- [livekit](https://github.com/livekit/livekit) - End-to-end stack for WebRTC. SFU media server and SDKs.
- [Pion WebRTC](https://github.com/pion/webrtc) - A pure Go implementation of the WebRTC API.

### C/C++

- [datachannel-wasm](https://github.com/paullouisageneau/datachannel-wasm) - C++ WebRTC Data Channels and WebSockets for WebAssembly in browsers.
- [HumbleNet](https://github.com/HumbleNet/HumbleNet) - A cross-platform networking library that works in the browser.
- [libdatachannel](https://github.com/paullouisageneau/libdatachannel) - C/C++ WebRTC network library featuring Data Channels, Media Transport, and WebSockets.
- [libpeer](https://github.com/sepfy/libpeer) - WebRTC Library for IoT/Embedded Device using C.
- [libwebrtc](https://github.com/webrtc-sdk/libwebrtc) - A C++ wrapper for binary release, mainly used for flutter-webrtc desktop (windows, linux, embedded).
- [MetaRTC](https://github.com/metartc/metaRTC) - A cross-platform webRTC SDK.
- [momo](https://github.com/shiguredo/momo) - WebRTC Native Client Momo.
- [Open WebRTC Toolkit](https://github.com/open-webrtc-toolkit/owt-client-native) - Client SDK for native Windows/Linux/Android/iOS applications is built upon the W3C WebRTC standard to accelerate the development of real time communication applications on these platform.
- [rawrtc](https://github.com/rawrtc/rawrtc) - WebRTC and ORTC with a little bit of RAWR.
- [WebUDP](https://github.com/seemk/WebUDP) - Minimal WebRTC datachannel server.

## Stun & Turn

- [Ayame](https://github.com/OpenAyame/ayame) - WebRTC Signaling Server.
- [Coturn](https://github.com/coturn/coturn) - Free open source implementation of TURN and STUN Server.
- [go-stun](https://github.com/ccding/go-stun) - A go implementation of the STUN client (RFC 3489 and RFC 5389).
- [Pion TURN](https://github.com/pion/turn) -  Go toolkit for building TURN servers and clients.
- [PeerServer](https://github.com/peers/peerjs-server) - Helps establishing connections between PeerJS clients.
- [singo](https://github.com/tockn/singo) - Simple WebRTC Signaling Server written in Go.
- [stun](https://github.com/nodertc/stun) - Low-level Session Traversal Utilities for NAT (STUN) client and server.
- [STUNTMAN](https://github.com/jselbie/stunserver) - An open source STUN server.
- [STUNNER](https://github.com/firefart/stunner) - Stunner is a tool to test and exploit STUN, TURN and TURN over TCP servers.
- [STUNner](https://github.com/l7mp/stunner) - A Kubernetes media gateway for WebRTC.
- [turn-rs](https://github.com/mycrl/turn-rs) - A pure rust implemented turn server.
- [violet](https://github.com/paullouisageneau/violet) - Lightweight STUN/TURN server.

## Projects

### Audio

- [babelcast](https://github.com/porjo/babelcast) - WebRTC audio broadcast server.
- [wireless-microphone](https://github.com/suda/wireless-microphone) - Turn any device into a wireless microphone over the internet.
- [webrtc-cli](https://github.com/gavv/webrtc-cli) - WebRTC command-line peer.

### Chat

- [Brie.fi/ng](https://github.com/holtwick/briefing/) - Secure direct video group chat.
- [Chitchatter](https://github.com/jeremyckahn/chitchatter) - Secure peer-to-peer chat that is serverless, decentralized, and ephemeral.
- [Databag](https://github.com/balzack/databag) - A tiny selfhosted federated messenger for the decentralized web.
- [jsxc](https://github.com/jsxc/jsxc) - Real-time xmpp chat application with video calls, file transfer and encrypted communication.
- [Gise Video Chat](https://github.com/vgiselbrecht/gise-video-chat) - Video chat application for your own web server.
- [otr.to](https://github.com/jermainee/otr.to) - A secure peer-to-peer chat in your web browser.
- [Pychat](https://github.com/akoidan/pychat) - Webchat via WebSockets/WebRTC that allows messaging/video call/screen sharing.
- [quickmeet](https://github.com/i-aryan/quickmeet) - A video chat/meeting webapp using WebRTC and WebSockets. Basically a Google Meet clone + a collaborative Whiteboard.
- [talkhouse](https://github.com/saalikmubeen/talkhouse) - WebRTC based peer to peer voice, video calling and messaging web app build with MERN stack.
- [tl-rtc-file-tool](https://github.com/tl-open-source/tl-rtc-file) - WebRTC P2P online web media streaming tool (for files, video, screen, live streaming, text) with management and statistical monitoring capabilities.

### File Transfer

- [filedrop](https://github.com/mat-sz/filedrop) - WebRTC E2E encrypted file transfer - React + Node.js.
- [Filegogo](https://github.com/a-wing/filegogo) - A file transfer tool that can be used in the browser webrtc p2p.
- [FilePizza](https://github.com/kern/filepizza) - Peer-to-peer file transfers in your browser.
- [GFile](https://github.com/Antonito/gfile) - Direct file transfer over WebRTC.
- [PairDrop](https://github.com/schlagmichdoch/PairDrop) - Local file sharing in your browser.
- [peermesh](https://github.com/perguth/peermesh) - Exchange files p2p and e2e encrypted over a fully meshed network in your browser using WebRTC.
- [Pipe File Transfer](https://github.com/Sh3b0/pft) - Web application for real-time file transfer using WebRTC.
- [ShareDrop](https://github.com/szimek/sharedrop) - Easy P2P file transfer powered by WebRTC - inspired by Apple AirDrop.
- [Snapdrop](https://github.com/RobinLinus/snapdrop) - A Progressive Web App for local file sharing.
- [WebDrop](https://github.com/subins2000/WebDrop) - Easiest group P2P File & Message transfer in browser with WebRTC.
- [WIFIDrop](https://github.com/nuzulul/wifidrop) - Instant transfer unlimited size of files over WIFI.
- [zero-share](https://github.com/ntsd/zero-share) - A client-side secure P2P file sharing using WebRTC.

### Game

- [allkaraoke](https://github.com/Asvarox/allkaraoke) - Online Karaoke game with pitch detection in your browser.

### Screen

- [Deskreen](https://github.com/pavlobu/deskreen) - Turns any device with a web browser into a secondary screen for your computer.
- [laplace](https://github.com/adamyordan/laplace) - Laplace is an open-source project to enable screen sharing directly via browser.
- [Odin](https://github.com/chukitow/odin) - An open-source screen recorder built with web technology.
- [pear-rec](https://github.com/027xiguapi/pear-rec) - Screenshot, screen recording, audio recording, and video recording software based on Electron.
- [picklecast](https://github.com/Evidlo/picklecast) - Share your screen to a projector with only a web-browser.
- [screensy](https://github.com/screensy/screensy) - Simple peer-to-peer screen sharing.
- [Spreen](https://github.com/IshaanOhri/Spreen) - The Screen Sharing App.
- [UltraScreen](https://github.com/w3yden/ultrascreen) - Share your screen.

### Server

- [Ant Media Server](https://github.com/ant-media/Ant-Media-Server) - Live streaming engine software that provides adaptive, ultra low latency streaming by using WebRTC technology with ~0.5 seconds latency.
- [Janus](https://github.com/meetecho/janus-gateway) - Open source, general purpose, WebRTC server designed and developed by Meetecho.
- [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge) - WebRTC-compatible Selective Forwarding Unit (SFU), i.e. a multimedia router.
- [Kurento](https://github.com/Kurento/kurento) - Kurento Media Server is responsible for media transmission, processing, loading and recording.

### Streaming

- [Coplay](https://github.com/Justineo/coplay) - Synchronizing video play between two peers.
- [Metastream](https://github.com/samuelmaddock/metastream) - Watch streaming media with friends.
- [MiroTalk WebRTC Live Broadcast](https://github.com/miroslavpejic85/mirotalkbro) - Allows to broadcast live video, audio and screen stream to all connected users (viewers).
- [OvenPlayer](https://github.com/AirenSoft/OvenPlayer) - OvenPlayer is JavaScript-based LLHLS and WebRTC Player for OvenMediaEngine.
- [Project Lightspeed](https://github.com/GRVYDEV/Project-Lightspeed) - A self contained OBS -> FTL -> WebRTC live streaming server. Comprised of 3 parts once configured anyone can achieve sub-second OBS to the browser livestreaming.
- [rtwatch](https://github.com/pion/rtwatch) - Watch videos with friends using WebRTC, let the server do the pausing and seeking.
- [TStream](https://github.com/qnkhuat/tstream) - Live streaming from your terminal.
- [VDO.Ninja](https://github.com/steveseguin/vdo.ninja) - Powerful tool that lets you bring remote video feeds into OBS or other studio software via WebRTC.

### Video Conference

- [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton) - Complete open source web conferencing system.
- [edumeet](https://github.com/edumeet/edumeet) - Multiparty web-meetings using mediasoup and WebRTC.
- [Galene](https://github.com/jech/galene) - Videoconferencing server that is easy to deploy and requires moderate server resources.
- [Jitsi Meet](https://github.com/jitsi/jitsi-meet) - Secure, Simple and Scalable Video Conferences that you use as a standalone app or embed in your web application.
- [kollokvium](https://github.com/coloquium/kollokvium) - Online meetings made easy, secure and private for everyone.
- [MiroTalk P2P](https://github.com/miroslavpejic85/mirotalk) - Simple, Secure, Fast Real-Time Video Conferences Up to 4k and 60fps, compatible with all browsers and platforms.
- [MiroTalk SFU](https://github.com/miroslavpejic85/mirotalksfu) - Simple, Secure, Scalable Real-Time Video Conferences Up to 4k, compatible with all browsers and platforms.
- [Nettu Meet](https://github.com/fmeringdal/nettu-meet) - Open source video conferencing system for tutors.
- [OpenVidu](https://github.com/OpenVidu/openvidu) - Create custom videoconference services with ease.
- [Plug-N-Meet](https://github.com/mynaparrot/plugNmeet-server) - WebRTC based Scalable, High Performance, Open source web conferencing system using Livekit.
- [persianmeet](https://github.com/sunmobiir/persianmeet) - Free Adobe Connect Alternatives.
- [quik](https://github.com/boratanrikulu/quik) - Free video conferencing over WebRTC in Go.
- [Roomler](https://github.com/gjovanov/roomler) - Multi-party Video Conferencing & Team Collaboration Tool using WebRTC (Janus Gateway).
- [React-VideoCall](https://github.com/nguymin4/react-videocall) - WebRTC-React App for Video Calling.
- [Talk](https://github.com/vasanthv/talk) - Group video call for the web. No signups. No downloads.
- [Trio Calls](https://github.com/arpitBhalla/trio-calls) - A multi-participant video call platform for calling across the world for free with screen sharing.
- [Wirow](https://github.com/wirow-io/wirow-server) - A full featured self-hosted video web-conferencing platform.

### Tool

- [flok](https://github.com/munshkr/flok) - Web-based P2P collaborative editor for live coding sounds and images.
- [neko](https://github.com/m1k1o/neko) - A self hosted virtual browser that runs in docker and uses WebRTC.
- [Parkerr](https://github.com/oxedom/parker) - Parking detection and monitoring webapp that runs entirely in the browser.
- [Project S.A.T.U.R.D.A.Y](https://github.com/GRVYDEV/S.A.T.U.R.D.A.Y) - A toolbox for working with WebRTC, Audio and AI.
- [remotecontrol-desktop](https://github.com/codext-remotecontrol/remotecontrol-desktop) - Remote Control Desktop is a robust, reliable and fast remote desktop software for Windows / macOS / Linux.
- [selkies-gstreamer](https://github.com/selkies-project/selkies-gstreamer) - Open-Source Low-Latency Linux WebRTC HTML5 Remote Desktop / GStreamer WebRTC Components of Selkies.
- [sshx](https://github.com/suutaku/sshx) - P2P SSH using WebRTC.
- [tiny-web-metaverse](https://github.com/takahirox/tiny-web-metaverse) - A web-based 3D virtual space lightweight framework with high flexibility, extensibility, and easy hosting, built on ECS architecture.
- [uProxy](https://github.com/UWNetworksLab/uProxy-p2p) - Browser extension that lets users share their internet connection.










## Miscellaneous

- [aiortc](https://github.com/aiortc/aiortc) - WebRTC and ORTC implementation for Python using asyncio.
- [cordova-plugin-iosrtc](https://github.com/cordova-rtc/cordova-plugin-iosrtc) - Cordova iOS plugin exposing the WebRTC W3C API.
- [Flutter-WebRTC](https://github.com/flutter-webrtc/flutter-webrtc) - WebRTC plugin for Flutter Mobile/Desktop/Web.
- [libwebrtc](https://github.com/aisouard/libwebrtc) - Google WebRTC implementation in a single static library.
- [Matchbox](https://github.com/johanhelsing/matchbox) - Painless peer-to-peer WebRTC networking for rust wasm (and native!).
- [OBS-studio WebRTC](https://github.com/CoSMoSoftware/OBS-studio-webrtc) - This is a fork of OBS-studio with generic support for webrtc.
- [peer-stream](https://github.com/inveta/peer-stream) - Lightweight WebRTC SDK for UnrealEngine PixelStreaming.
- [Python WebRTC](https://github.com/MarshalX/python-webrtc) - Python extension that provides bindings to WebRTC M92.
- [React-Native-WebRTC](https://github.com/react-native-webrtc/react-native-webrtc) - A WebRTC module for React Native.
- [rings](https://github.com/RingsNetwork/rings) - Rings is a structured peer-to-peer network implementation using WebRTC, Chord algorithm, and full WebAssembly (WASM) support.
- [rpi-webrtc-streamer](https://github.com/kclyu/rpi-webrtc-streamer) - Web Cam server on the most popular Raspberry PI hardware.
- [WebRTC.rs](https://github.com/webrtc-rs/webrtc) - Pure Rust implementation of WebRTC stack, which rewrites Pion stack in Rust.
- [WebRTC-iOS](https://github.com/stasel/WebRTC-iOS) - A simple native WebRTC demo iOS app using swift.
- [webrtc-java](https://github.com/devopvoid/webrtc-java) - WebRTC for desktop platforms running Java.
- [WebRTC Android](https://github.com/GetStream/webrtc-android) - A versatile WebRTC pre-compiled Android library that reflects the recent WebRTC updates to facilitate real-time video chat for Android and Compose.
- [WebRTC for Unity](https://github.com/Unity-Technologies/com.unity.webrtc) - WebRTC package for Unity.

## Contribute

Contributions are welcome!

See the [Contribution Guidelines](https://github.com/nuzulul/awesome-webrtc/blob/main/CONTRIBUTING.md).
