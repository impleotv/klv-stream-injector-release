Change Log
==========

### Ver. 2.1.0 (12/08/24)
- low level modifications
- MisbCore VMTI modifications
	- Add MISB903.6 support 

### Ver. 2.0.5 (19/05/24)
- low level 
	- Complete support for pull demux with MPEG-PROGRAM input
	- Complete fix for IIS crash

### Ver. 2.0.0 (6/05/24)
- Add JWT license

### Ver. 1.13.0 (30/04/24)
- Move to .Net 4.7.2

### Ver. 1.12.0 (26/03/24)
- Modify NodeInfo format
Low level:
- Improving performance in D3d rendering
- Fixing VideoOverlayMixer in handling I420 pixel format

### Ver. 1.11.5 (24/03/24)
- Update MisbCore
	- Remove length from VMTI Location (tag 17)
	- Remove length from VMTI Velocity and Acceleration DLP 
- Improving the playback smoothness in D3d rendering
- DirectX mode playback improvements.
- Generic Flag Data (tag47) Versions 13 through 16 of ST 0601 unintentionally inverted the column definitions; 
Low level changes:
- Add support for EVR renderer
- Add debug monitoring points for D3D9 Renderer
- Add an ini patch to disable footer search

### Ver. 1.11.1 (22/02/24)
- Update low level
- Add option for async callback of sync frames
- Modify StCore interface

### Ver. 1.10.15 (29/01/24)
- Update low level

### Ver. 1.10.11 (03/012/24)
- Update low level
- Fix vmti number of targets. Move filehelper to misbCore (json2Klv)

### Ver. 1.10.10 (21/12/23)
- Update low level

### Ver. 1.10.4 (12/10-/23)
- Fix long VMTI tracker (over 14 items)

### Ver. 1.10.3 (23/08/23)
- Low level update. 
- Support the sps information provided in an rtp packet with a format STAP-A 
- Fix the SequenceHeaderInsertionOnKeyFrames property did not reach its destination in the DVR mode

### Ver. 1.10.2 (16/07/23)
- Fix BER-OID Encoding/Decoding for VMTI Target ID

### Ver. 1.10.1 (27/06/23)
- Low level update. Decoder memory leak fix

### Ver. 1.10.0 (23/05/23)
- Low level update. FFmpeg version change

### Ver. 1.9.5 (03/04/23)
- Update Low level
- Fix Metadata_AU_cell () in KlvSource filter. Applicable to SYNC_KLV use case

### Ver. 1.9.4 (14/08/22)
- Update MisbCore (fix VMTI target id)

### Ver. 1.9.3 (09/08/22)
- Add tag 122, 138, 139
- Low level update 

### Ver. 1.9.2 (07/08/22)
- Add tags 115, 116, 121, 128
- Update low level

### Ver. 1.9.1 (17/07/22)
- Update low level
- New Node info support
- Set Klv PID without default packet when REST interface is operational
- Help now generated with mkdocs

### Ver. 1.8.12 (01/02/22)
- Update remuxer

### Ver. 1.8.11 (19/12/21)
- Update low level

### Ver. 1.8.10 (23/11/21)
- Update low level
- Add time restricted license support
- Move to vc142

### Ver. 1.8.9.2 (11/11/21)
- Update VS runtime to v142

### Ver. 1.8.9.1 (02/11/21)
- Update MisbCore

### Ver. 1.8.9 (14/10/21)
- Add FrameAccuracyRequiresSequenceHeaders config 
- Low level update

### Ver. 1.8.7.5 (13/05/21)
- MisbCore update
- Low level update

### Ver. 1.8.7.4 (05/05/21)
- MisbCore fix
- Comiled with VS2019
- Low level update

### Ver. 1.8.7.1 (05/04/21)
- Allow integers in addition to float for some tags
- Low level update

### Ver. 1.8.7 (25/03/21)
- Use UTC time
- Fix HLS duration (with discontinuity) 
- Low level update

### Ver. 1.8.6 (18/01/21)
- Add ContiguousDemuxedVideo
- Low level update

### Ver. 1.8.5.0
- Update low level
- Fix Big Endian Unicode in UTF-16

### Ver. 1.8.4.3
- Update low level

### Ver. 1.8.4.2
- Fix Tag 6, 7 special value
- Fix casting for 32 bit special values

### Ver. 1.8.4.1
- Fix Tag 20 ( Sensor Relative Roll Angle) validation

### Ver. 1.8.4
- Fix RTSP (tcp)
- Enable FIPS Compliant authorization

### Ver. 1.8.3
- Low level update (HLS performance improvements)

### Ver. 1.8.2.2
- Modify existingKlv pid behavior 

### Ver. 1.8.2
- Low level update (StCore 3.8.2)

### Ver. 1.8.1
- Low level update (StCore 3.8.1)
- MisbCore RAW Klv processing

### Ver. 1.8.0
- Low level update (StCore 3.8.0)
- MisbCore
- Move to .NET 4.6.1
- Add Audio capture

### Ver. 1.7.18
- Low level update (StCore 3.7.18)
- Movie Win32 binaries of Encoder Process to a subfolder

### Ver. 1.7.17
- Low level update (StCore 3.7.17)
- Frame Accuracy stability fixes for reverse playback

### Ver. 1.7.16
- Add Low lalency mode

### Ver. 1.7.15
- Low level update

### Ver. 1.7.14.1
- Fix  each stop->start creates additional output channel with the same IP and port.

### Ver. 1.7.13
- Fix frame grabber

### Ver. 1.7.12
- Add grabber

### Ver. 1.7.11
- Low delay fixes
- Adding option to modify incoming PTS in Injector according to local CPU time

### Ver. 1.7.10
- Low level update
- 0.0.0.0 binding

### Ver. 1.7.10
- Low level update - StCore 3.7.10

### Ver. 1.7.7
- Low level update - StCore 3.7.7

### Ver. 1.7.6
- Low level changes (Injector robustness)
- Fix missing Klv after seek
- Fix audio pid mux

### Ver. 1.7.5
- Update low level to 3.7.5

### Ver. 1.7.2
- Update low level to 3.7.4

### Ver. 1.7.1
- Update low level
- Add logger

### Ver. 1.7.0
- BER-OID tags
- Synthetic Video fixes in low level filters and StCore.dll
- Based on SDK 3.7.0

### Ver. 1.3.1
- Add more logs

### Ver. 1.3.0
- Add .json and .csv offline ingest

### Ver. 1.2.9
- Low level update (ver. 3.5.9). 
- Add Synthetic video (Flywheel)

### Ver. 1.2.8
- Low level update (ver. 3.5.3). 
- Add REST GET videoPts method.

### Ver. 1.2.7
- VC141 and Boost 1.71 

### Ver. 1.2.6
- Low level StCore update to ver 3.5

### Ver. 1.2.5
- Low level StCore update

### Ver. 1.2.4
- Low level StCore update
- License persistence

### Ver. 1.2.3
- Insert private data

### Ver. 1.2.2
- Transcode 104.5 to MISB 601 added

### Ver. 1.2.1
- Low level SDK update.

### Ver. 1.2.0
- Low level SDK update.

### Ver. 1.1.1
- Low level SDK update.

### Ver. 1.1.0
- Low level SDK update.

### Ver. 1.0.11
= Json udp in added.
- Internal code rewrite
- Log writes to ApplicationData instead of CommonApplicationData
- Security Metadata Set encoding in json default packet fix

### Ver. 1.0.10
- Low level update
- Udp in added
- log4net added
- default packet is now optional

### Ver. 1.0.9
- Low level changes
- Fix Init returns true on success

### Ver. 1.0.8
- Low level changes
- Compressed video frames DTS reporting.

### Ver. 1.0.7
- REST interface added

### Ver. 1.0.6
- Low loevel updated
- Counters show rate calculated by both timestamp and time

### Ver. 1.0.5
- File target added
- Input Arguments change
- EG601 xml parser rewritten

### Ver. 1.0.1
- Add file watcher

### Ver. 1.0.0
- Initial version.



    