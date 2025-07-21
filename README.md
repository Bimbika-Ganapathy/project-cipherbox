CipherBox

# CipherBox - Secure File Storage & Sharing


CipherBox is a secure, end-to-end encrypted file storage and sharing application built with Electron.js and Node.js. It provides a secure way to store, access, and share your files with strong encryption and access control.

## Features

- 🔒 End-to-End Encryption (AES-256 & RSA-2048)
- 👥 User Authentication & Authorization
- 📁 Secure File Storage & Sharing
- 🔑 Secure Key Management
- 🖥️ Cross-Platform Desktop Application
- 🔄 Real-time File Synchronization
- 👨‍💻 Admin Dashboard for User Management

## Prerequisites

- Node.js (v14 or later)
- npm (comes with Node.js)
- Git (for cloning the repository)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/CipherBox.git
   cd CipherBox
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## Running the Application

### Development Mode
```bash
npm start
```

### Production Build
```bash
npm run build
# The built application will be in the 'dist' directory
```

## Security Features

- **Encryption**: All files are encrypted client-side before upload
- **Secure Authentication**: Password hashing with SHA-256
- **Key Management**: Secure key exchange using RSA-2048
- **Session Security**: Encrypted session management

## Project Structure

```
CipherBox/
├── Client/               # Client-side application
├── Server/               # Server-side code
│   ├── Endpoints/        # API endpoints
│   └── Logging/          # Server logging
├── Common/               # Shared code
│   ├── Constants/        # Application constants
│   ├── Encryption/       # Encryption modules
│   └── Files/            # File handling
├── Pages/                # UI pages
├── assets/               # Static assets
├── Main.js               # Electron main process
└── package.json          # Project configuration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Support

For support, please open an issue in the GitHub repository.

## Acknowledgments

- Built with Electron.js and Node.js
- Uses crypto-js for cryptographic operations
- Inspired by secure file storage solutions

---

**Note**: This is a secure application. Always keep your login credentials and encryption keys safe.
