# Home server

- [Emby server](emby-server)
- [MiniDLNA](minidlna)
- [Transmission](transmission)
- [Samba](samba)

## Emby server

- Http (https) server for Mobile app or Smart TV apps.
- Can be enabled DLNA server.

More info: [https://emby.media/](https://emby.media/)

## MiniDLNA

Is a simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients.

More info: [https://sourceforge.net/projects/minidlna/](https://sourceforge.net/projects/minidlna/)

## Transmission

Open-source cross-platfoorm BitTorrent client.

## Samba

The server part of the Samba program, which allows you to access network drives on various operating systems using the SMB / CIFS protocol.

## Requirements:
- Docker
- Docker-compose
- Git

## How to use:

#### Clone:

```bash
git clone https://github.com/flexnst/home-server.git home-server
cd home-server
```

#### Link your storage directory

```bash
rm -rf ./storage
ln -s /path/to/your/storage/directory ./storage
```

#### Start services
```bash
docker-compose up -d
```