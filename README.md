
---

## Prerequisites
Before running the project, ensure you have the following installed:

- **C++ Build Tools**:
  - CMake (`sudo apt-get install cmake`)
  - FFmpeg libraries (`sudo apt-get install libavcodec-dev libavformat-dev libavutil-dev`)
- **Python** (3.7+):
  - Install Python from [python.org](https://www.python.org/).
- **Supabase Account**:
  - Create a project at [supabase.io](https://supabase.io).

---

## Setup Instructions

### 1. Set Up Supabase
1. Go to [Supabase](https://supabase.io) and create a new project.
2. Enable **Authentication** (email/password or third-party providers).
3. Enable **Realtime** for signaling (e.g., WebRTC signaling).
4. Create a `users` table in the database to store user information.

### 2. Build the C++ Library
1. Navigate to the `cpp` directory:
   ```bash
   cd cpp
