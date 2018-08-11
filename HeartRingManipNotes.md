$c5c0 to $c600 is unappraised rings; the IDs are https://github.com/Drenn1/ages-disasm/blob/master/constants/rings.s



Starting from a rupee:
5 digs to another rupee
4 digs to another rupee
2 digs to a heart
2 digs to a heart
3 digs to a rupee

These values are used to know where you are in RNG

Checking under 3 rupees, 29 rupees in inventory:
- Transition to maple, bomb drop on rock; Nothing
  - 2 digs; red luck ring
  - 3 digs; red luck ring
  - 4 digs; red luck ring
- transition, right, left 29 rupees in inventory:
  - transition to maple, nothing under rock; Nothing
    - 1 dig; Quicksand Ring
    - 2 digs; Quicksand Ring
- transition right, left, right, left, 29 rupees in inventory:
  - transition to Maple; bombs under rock; Peace Ring
    - 1 dig; Whimsical ring
    - 2 digs; Whimsical ring
    - 3 digs; Gasha Ring, potion
    - 4 digs; Gasha Ring
    - 5 digs; Gasha Ring
- transition right, left, right, left, 29 rupees in inventory:
  - 1 dig to fairy, nothing under rock
    - transition to maple
      - 0 digs; red luck ring
      - 1 dig; red luck ring
      - 8 digs;



Start from the quickest

- Get the two rupees
  - Go to Maple
    - 0 - 6 digs; nothing
    - 7 digs; Red luck ring
    - 8 digs; Red luck ring
  - R,L,Maple
    - 0-4 digs; nothing
    - 5-7 digs; Quicksand ring
    - 8 digs; Whisp ring
  - R,L,R,L,Maple
    - 0-5 nothing
    - 6-7 red luck ring
    - 8 nothing
  - R,L,R,L,R,L,Maple
    - 5-6 Peace ring
    - 7 Protection ring
- Get the three rupees
  - Maple
    - 2-3 digs; red luck ring
    - 4; toss ring
    - 5; Zora Ring
  - RLM
    - 1-3 digs; Quicksand Ring
    - 4-5 digs; whisp ring
  - RLRLM
    - 0 Digs; Peace Ring
    - 1 Dig; Whimsical,Potion
    - 2 Digs; Whimsical
    - 3-5 Digs; Gasha, Potion
    - 6 digs; Zora Ring
  - RLRLRLM
    - 0 digs; Peace Ring
    - 2-3 digs; Peace
    - 4-5 digs; protection
    - 6; Quicksand
- Get 3 rupees and heart
  - Maple
    - 0-1; Red Luck
    - 2; Toss
    - 3; Zora
  - RLM
    - 0; Quicksand
    - 1; $39 Whisp
    - 2;


RNG after 3 rupees and 2 hearts: $c582
After RL: $4284

Can't continue digging after 3R2H ,RL because beetles are dug.

More tiles can be dug after 3R2H, RLRL.

3R2H
- Maple; $52
  - 1 dig; $7C
  - Nothing after 1 dig
- RL
  - Maple; $79
    - Nothing after digs
  - 1 dig to rupee
    - Maple; nothing
      - nothing after digging
  - RL
    - Maple; $79
      - 1-2D; $5d
      - 5-8D; $52
    - 1D
      - Maple; $5d
        - 1D; $5d
        - 4-7D; $52
    - 2D
      - Maple; $5D
        - 3-6D; $52
    - 3D
      - Maple; $5d
        - 3D; $52
    - Dig until rupee
      - Maple; $52
        - 1D; $52
        - Nothing after 1 dig
      - Dig heart
        - Maple; $52
        - Dig 5 rupees
          - Maple
    - RL
      - Maple; $7b
        - 1D; $7b
        - 2-3D; $7f
        - 5d; $63
      - Dig until rupee
        - Maple; $7b
          - 1D; $42
        - Dig 5 rupees
          - Maple; $42
      - RL
        - Maple; $54, potion

Potential find:
- hard reset
- mash through menu
- dig up 3 rupees and two hearts in that order
- RLRLRLRL
- Maple
