# Instructions for Creating the zbank_testnet Work
1. Open terminal (pip install geth)
2. Create node1_zbank and node2_zbank (code is in Creating Nodes file)
3. Pull addresses for both node1_zbank and node2_zbank
4. Open Geth in the terminal
5. Run ./puppeth within the terminal
6. PROMPT 1: Please specify a network name to adminsiter.  <zbank1_testnet>
7. PROMPT 2: What would you like to do? <2 Configure New Genesis>
8. PROMPT 3: What would you like to do? <1 Create New Genesis from Scratch>
9. PROMPT 4: Which consensus engine to use? <2 Clique - proof-of-authority>
10. PROMPT 5: How many seconds should blocks take? <   >
11. PROMPT 6: Which accounts are allowed to seal? <enter the addresses for node1_zbank and node2_zbank>
12. PROMPT 7: Which accounts should be pre-funded? <enter the addresses for node1_zbank and node2_zbank again>
13. PROMPT 8: Should the precompile-addresses be pre-funded with 1 wei? <no>
14. PROMPT 9: Specify your chain/network ID if you want an explicit one. <30405>
15. PROMPT 10: What would you like to do? <2 Manage Existing Genesis>
16. PROMPT 11: What would you like to do? <2 Export Genesis Configuration>
17. Save to directory