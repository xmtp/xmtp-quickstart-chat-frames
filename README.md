# Render Chat Frames in Your Application

![xmtp](https://github.com/xmtp/xmtp-quickstart-reactjs/assets/1447073/3f2979ec-4d13-4c3d-bf20-deab3b2ffaa1)

<video controls src="https://github.com/fabriguespe/xmtp-quickstart-frames/assets/1447073/adf38f79-703c-4759-8523-4feb0ebb2d0e" width="100%" type="video/mp4">
Your browser does not support the video tag.
</video>

## Installation

```bash
yarn install
yarn dev
```

This part of the guide focuses on how to render Frames within your application, making the frames interactive and visually integrated. It includes:

- **Validating frame URL**: The validation of frame URLs is performed using a regular expression to identify URLs within the message content. Once a URL is identified, it's processed to extract metadata, including frame information.

- **Rendering Frames**: Frames are rendered by dynamically creating a `Frame` component based on the extracted frame information. This component is responsible for displaying the frame's content, including images, titles, and interactive buttons.

- **Sign XMTP Payload**: Use `@xmtp/frames-client` to sign and send frame actions securely. This package facilitates interoperable communication by ensuring that messages are securely signed and verifiable.

## Other resources

These are the foundational tools that allow developers to create, sign, and manage Frames. The protocol libraries are essential for interacting with the XMTP network at a lower level, handling the creation of frames, signing payloads, and managing frame actions. Key aspects include:

- [**OnChainKit Documentation**](https://onchainkit.xyz/xmtp/introduction): Discover how OnchainKit seamlessly incorporates XMTP payloads.
- [**Frames.js Documentation**](https://framesjs.org/reference/js/xmtp): Learn about the integration of XMTP payloads within FrameJS.
- [**Experience XMTP on xmtp.chat**](https://xmtp.chat/): Engage with Frames firsthand by trying them on the official XMTP client platform.
- [**Open Frames**](https://github.com/open-frames/standard/blob/v0.0.1/README.md): XMTP contributes to the Open Frames standard, fostering interoperability and open standards.
