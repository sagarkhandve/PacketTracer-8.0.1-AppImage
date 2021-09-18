
Download And Run [Cisco Packet Tracer - 8.0.1 [AppImage]](https://github.com/sagarkhandve/PacketTracer/releases/download/v8.0.1/PacketTracer-8.0.1.AppImage)

1. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/sagarkhandve/PacketTracer-8.0.1/releases/download/v8.0.1/PacketTracer-8.0.1_x86_64.AppImage
   chmod +x PacketTracer-8.0.1_x86_64.AppImage
   ```
2. Run:

   ```shell
   ./PacketTracer-8.0.1_x86_64.AppImage
   ```

A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Packet Tracer in AppImage form.

How to use it?

1. Clone this repository and `cd` into it.
    ```shell
    git clone https://github.com/sagarkhandve/PacketTracer-8.0.1.git
    cd PacketTracer-8.0.1/
    ```
2. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Build it:

   ```shell
   ./pkg2appimage PacketTracer-8.0.1.yml
   ```

4. After a short break you should get an executable inside `out/` directory.
