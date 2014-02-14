== WebRTC2SIP Precise Build

This is a build of WebRTC2SIP for Ubuntu Precise Pangolin 12.04

This is an apt repository. However, you cannot reference it directly hosted on github.

You must clone locally and refer to it directly:

    git clone https://github.com/sous/webrtc2sip-precise
    ( echo deb file://`pwd`/webrtc2sip-precise precise main
      echo deb-src file://`pwd`/webrtc2sip-precise precise main ) > /etc/apt/sources.list.d/webrtc2sip-precise.list

The gpg key for this repo can be imported using:

    curl https://raw.github.com/sous/webrtc2sip-precise/master/apt-key.gpg | sudo apt-key add -

