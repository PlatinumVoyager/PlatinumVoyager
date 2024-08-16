*"Be strong and courageous. Do not be afraid or terrified because of them, for the Lord your God goes with you; **he will never leave you nor forsake you.**"* - Deuteronomy 31:6

### Welcome visitor,

This Github account officially represents the capabilities possessed as an individual pursuing more sophisticated methods of obtaining advanced technical literacy in the field of Cybersecurity and Offensive Cyberspace Operations.

<hr>

## Mind Detour: Current thought for a future project (one of multitudes)

* An "in-memory" DRM (Direct Rendering Manager) bitmap framebuffer control tool for low level screen capture functionality.</li>
  * Could utilize extensions for X11 to target the display server or a custom/modified video compositor for subsequent success in further operations.
  * Taking information stored about each frame buffer (/dev/dri/card0, etc) and using it to further establish acceptable forms of operations.

  * May consider implementing a *Bitwise XOR Copy* style algorithm for capturing specific regions of the screen (i.e - targeting/reading different areas of memory) more efficiently.
    * Especially if such areas of memory are within a double buffer/page flipped memory region in which the frame buffer has enough memory (virtual) to store the current bitmap within half of its
      alloted address space contiguously, and the other half being stored before it is processed.
        * Can such information from the other half of the double buffer not in use be "readily" sent, stored, and updated as to appear to be peering into the future before it is sent to the main display?
          * Whilst obtaining information regarding the GPU's current display modes via FB (frame buffer) interrogation, taking a closer look at the refresh rate, could this value be modified to lower the current refresh cycle further to increase the speed in which the frames are read by the operator before being sent to the main display driver?

Easy explantion: It should be possible to capture bitmap scalar data frames (think about a single picture of your screen) before they are sent to the main display (monitor, TV, etc) in such a way that the screen refresh rate (think FPS) is incrementally lowered (would need to compensate for avg CPU load) over a set period to "allow" time to utilize the CPU without affecting the end-users reactionary gap (the time between noticing discrepancies within their environment) to stay undetected.

***NOTE:** Skeleton C source files have been developed, thus it seems such a process is indeed possible. Time and true low level understanding/techniques will consume a considerable amount of time.*

<img src="https://github.com/user-attachments/assets/a0689f2d-eec1-4d73-aca7-3841dc417f7f" style="width: 80%; height: 80%">

<hr>

<img src="https://github.com/user-attachments/assets/711ea7bb-f383-4e42-a35a-76f488d2c931">

## Currently: Modifying ALL static website content for future updates

<li>Re-aligning page frame borders to force a more reliable/readable content fixture.</li>
<li>Improving internal JavaScript to fix background binary text transitions.</li>
<li>Reevaluating "work-in-progress" Projects source files.</li>
<li>Minor changes to every source file under the current local server directory structure.</li>
<li>Adding inbuilt OOB (Out of Bounds) corrupted stack frame relay proxy execution browser exploit to capture/modify site wide visitor data. It's just a joke, relax :)</li>

[comment]: # (Ridiculous how these comments are to be approached as well as the # of br's brrrrrrrr)

</br>
</br>

## Working on Project: OnionBatch
<img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/db5895f2-9441-476f-9634-cb158fc1e2e0" align="left">

<h3>About</h3>
<p>Written in C++ OnionBatch/BatchOnion loader is a fast multi-media downloader that egresses outbound traffic through the TOR network.<p>

<h3>Features</h3>
<li>SOCKS5/SOCKS4 Proxy support.</li>
<li>Network egress via the <a href="https://www.torproject.org/">TOR</a> anonimyzing relay network.</li>
<li>Concurrent download initialization methods.</li>
<li>Stable libcurl based backend for handling requests, etc.</li>
<li>Fast and efficient user-based graphical interface.</li>

</br>
</br>

## Development Update: OnionBatch GUI
<img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/17b1a549-12db-4e05-8079-d2ecdf1ba3dc" style="width: 80%; height: 80%;"></img>

</br>
<img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/df2d1539-8cfb-4739-af8c-af3e997f7844" style="width: 80%; height: 80%;"></img>


<hr>
</br>

## Released the QuietWeeping HTTP Server (March 2024)
<!-- <img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/4a4178d3-08f6-4d35-a1bb-ea9047eb3fd4"> -->

<img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/a44f574c-35ae-450c-9708-2fe09e5892da" align="left">

<!-- HELLO THERE ;) <img src="https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/4a4178d3-08f6-4d35-a1bb-ea9047eb3fd4" align="right"> -->

</br>

* To get up-to date with the latest `Quiet Weeping Server` project click <a href="https://github.com/PlatinumVoyager/QuietWeeper" title="Official QuietWeeper HTTP Server Github repository">here</a>.
* To download the latest release (v1.2.2) with the associated source code and pre-built binary executable click <a href="https://github.com/PlatinumVoyager/QuietWeeper/releases/tag/v1.2.2" title="Official QuietWeeper v1.2.2 release">here</a>.

</br>
</br>
</br>
</br>
</br>

## Released the BRIGHTSTAR SSDP framework (October 2023)

* <p>To view the current project with a more detailed overview click <a href="https://github.com/PlatinumVoyager/BrightStar">here</a>.</p>
* <p>To download the latest v1.0 release (zip archive) you can obtain it from <a href="https://github.com/PlatinumVoyager/BrightStar/releases/tag/v1.0">here</a>.</p>

![bstar_converge](https://github.com/PlatinumVoyager/PlatinumVoyager/assets/116006542/c5786883-6e0b-47e5-94e8-d892f2166631)

<hr>

## Currently

* Learning the [Rust](https://www.rust-lang.org/) programming language.
  * Planning to create:
    * Android based administration tool (android debug bridge wrapper in Rust)
    * Linux agent w/ encrypted socket communications, obfuscation routines at runtime, etc.

* Raw 802.11 a/b/g/n 2.4 GHz wireless deauthentication framework (Written in C)

* In singular development of [BrightStar](https://github.com/PlatinumVoyager/BrightStar).
  * Adding small scale updates on occasion.
  * Planning future roadmap for v2.0 feature set.
 
* Learning **Software Reverse Engineering** with the [Ghidra](https://ghidra-sre.org/) SRE framework.
  * Interested in building modular plugins with Python [(]()[Jython](https://www.jython.org/)[)]().
  * Static binary analysis.
  * Exploit development and security posture assessments.
 
* Developing a DLL injection framework on Windows for process interaction and manipulation.
  * Systematically identify vulnerable applications which allow the availability of non-privileged DLL hooking/injection, etc.
  * Target specific applications or a subset of specific applications to test against.
  * Future: Encrypted DLL loader (Encrypt target DLL files while in memory until they need to be decrypted for runtime execution)

