## Packet sniffer using the PCAP (Packet Capture) API and filter out TCP packets.

# Packet Sniffer Implementation

Follow these steps to set up and run the packet sniffer on your Linux system:

1. **Open VirtualBox and Start the Virtual Machine**:
   - Launch VirtualBox and start the desired operating system image.

2. **Open Terminal and Create a C File**:
   - Open a terminal within the virtual machine.
   - Create a new C file using a text editor. For example:
     ```bash
     nano sniffer.c
     ```

3. **Paste the Code in the C File**:
   - Copy and paste the provided C code (packet sniffer) into the `sniffer.c` file.

4. **Compile the C Code**:
   - Compile the C code using the `gcc` compiler. Replace `filename.c` with the actual name of your C file and `executionname` with the desired name for the compiled binary. For example:
     ```bash
     gcc sniffer.c -o sniffer 
     ```

5. **Run the Compiled Binary**:
   - Execute the compiled binary with `sudo` to run the packet sniffer. This step requires administrative privileges due to the nature of packet capturing.
     ```bash
     sudo ./sniffer
     ```

6. **Capture Packets**:
   - The packet sniffer will start capturing TCP packets on the specified network interface. You can modify the code or the filter expression to capture packets based on different criteria as needed. Press `Ctrl+C` to stop the packet sniffer when you're done.

   
