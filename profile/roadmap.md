# iamai-core

## Detailed Product Roadmap

### Phase 1: Foundation - Local Chat Companion
- **Core Features**
  - Basic text chat interface
  - Local-only operation with no cloud dependencies
  - Cross-platform support (Windows, macOS, Linux)
  - Simple installation process
- **Technical Milestones**
  - Self contained C/C++ AI inference core
  - React/Next.js frontend chat, served via Crow
  - SQLite data storage implementation
  - Unity and Unreal Engine plugins

### Phase 2: Multimodal Expansion
- **Core Features**
  - Voice interface with natural conversation
  - Audio processing and response
  - Image recognition capabilities
  - Android app with earbud interface
- **Technical Milestones**
  - Speech-to-text and text-to-speech integration
  - Audio processing pipeline
  - Image processing capabilities
  - Remote JNI native Android implementation

### Phase 3: Personal Knowledge Integration
- **Core Features**
  - Document ingestion (text files, PDFs, emails)
  - Social media history integration
  - Secure personal data storage
  - Knowledge retrieval based on context
- **Technical Milestones**
  - Document processing pipeline
  - Secure storage architecture with encryption
  - Contextual RAG retrieval system
  - Expanded C/C++ core capabilities

### Phase 4: Continual Learning Framework
- **Core Features**
  - Real-time learning from user interactions
  - Preference adaptation
  - Conversational memory
  - Personal context awareness
- **Technical Milestones**
  - Lightweight fine-tuning mechanism
  - Memory systems for short/long-term recall
  - Learning rate optimization
  - User feedback incorporation

### Phase 5: Agentic Desktop Assistant
- **Core Features**
  - Screen understanding capabilities
  - PC GUI interaction automation
  - Workflow assistance and optimization
  - Task completion across multiple applications
- **Technical Milestones**
  - Screen recognition system
  - Input simulation (keyboard/mouse)
  - Task planning architecture
  - Safety mechanisms for automated actions

### Phase 6: Latent Pool Protocol
- **Core Features**
  - Secure peer-to-peer AI communication
  - Trust management system
  - Distributed knowledge sharing
  - Collaborative problem-solving
- **Technical Milestones**
  - Transformer AI inner latent sharing
  - Intrinsic contribution attention system
  - ZeroMQ PUB/SUB implementation for distributed communication
  - Public key infrastructure for node identification

## Development Principles
- Privacy-first design at every stage
- Minimize resource requirements for accessibility
- User control over all data and learning
- Open-source development for transparency
