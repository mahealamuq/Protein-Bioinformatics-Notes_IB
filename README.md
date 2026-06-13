# Protein-Bioinformatics-Notes
The aim of this repository is to explain how bioinformatics can be used to study proteins from their amino acid sequence and connect this information to protein structure, function, interaction, and biological pathways.

---
## 1. Introduction to Protein Bioinformatics

Proteins are biological molecules made from amino acids. Each protein has a sequence, structure, and function.

Bioinformatics helps answer questions such as:

- What structure does a protein sequence form?
- Does the protein contain alpha helices or beta strands?
- Where is the protein located in the cell?
- What other proteins does it interact with?
- What biological pathway is it involved in?

**The repository is based on two main topics:**

1. Protein sequence to secondary structure
   
2. Protein sequence to function and biological systems

---
## 2. Amino Acids and Protein Sequence

Proteins are made from amino acids. Amino acids have different chemical properties that influence protein structure and function.

**Amino Acid Groups**

| Group | Description | Examples |
|---------|-------------|----------|
| Basic | Accept protons | Lysine, Arginine |
| Acidic | Donate protons | Aspartic acid, Glutamic acid |
| Polar | Contain polar groups | Serine, Threonine |
| Nonpolar | Hydrophobic | Valine, Leucine |
| Aromatic | Ring structures | Phenylalanine, Tyrosine |
| Special | Unusual structural role | Proline, Cysteine |

**Notes**

- **Proline** is important because it can disrupt alpha helices due to its rigid ring structure.
- **Cysteine** can form **disulphide bridges**, which help stabilize protein structure.

<img width="1055" height="826" alt="image" src="https://github.com/user-attachments/assets/2d269f83-bae6-41bd-8598-e141cfbadeb1" />

---

## 3. Levels of Protein Structure

| Structure Level | Meaning |
|----------------|---------|
| Primary structure | Amino acid sequence |
| Secondary structure | Local structures such as alpha helices and beta sheets |
| Tertiary structure | Full 3D folding of one protein chain |
| Quaternary structure | Interaction between multiple protein chains |

<img width="1086" height="748" alt="image" src="https://github.com/user-attachments/assets/360622e9-69e3-4710-8851-7d0044748af8" />

---
## 4. Protein Secondary Structure

Secondary structure refers to local folding patterns in proteins.

**Main Classes**

- Alpha helix
- Beta strand
- Beta sheet
- Turn
- Random coil

**Secondary Structure Symbols**

| Symbol | Meaning |
|---------|---------|
|  H | Alpha helix |
|  E | Beta strand |
|  C | Coil |
|  T | Turn |


### Example

**Protein Sequence**

```text
GHWIATRGQLIREAYEDYRHFSSECPFIP
```

**Predicted Secondary Structure**

```text
CEEEEECHHHHHHHHHHHCCCHHHCCCCC
```

### Position-by-Position Representation

| Position | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 |
|----------|---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| Sequence | G | H | W | I | A | T | R | G | Q | L | I | R | E | A | Y | E | D | Y | R | H | F | S | S | E | C | P | F | I | P |
| Structure | C | E | E | E | E | E | C | H | H | H | H | H | H | H | H | H | H | H | C | C | C | H | H | H | C | C | C | C | C |



### Interpretation

This protein begins with a short **β-strand region (E)**, followed by a long **α-helix region (H)** in the middle of the sequence. The protein ends with several **coil regions (C)** interspersed with a short α-helix segment.

---

## 5. Alpha Helix

An **alpha helix (α-helix)** is a spiral-shaped secondary structure commonly found in proteins.

### Key Features

- Usually has **3.6 amino acids per turn**
- Stabilised by **hydrogen bonds**
- The oxygen atom of residue **i** forms a hydrogen bond with the nitrogen atom of residue **i + 4**
- Common in **globular proteins**, **membrane proteins**, and **fibrous proteins**
- Contributes to protein stability and function

### Alpha Helix Characteristics

| Feature | Description |
|----------|-------------|
| Shape | Right-handed spiral |
| Residues per turn | 3.6 |
| Stabilisation | Hydrogen bonds |
| Hydrogen Bond Pattern | Residue *i* to residue *i + 4* |
| Location | Many globular, membrane, and fibrous proteins |

### Examples of Proteins Containing Alpha Helices

| Protein | Function |
|----------|----------|
| Myoglobin | Oxygen storage in muscle cells |
| Haemoglobin | Oxygen transport in blood |
| Bacteriorhodopsin | Light-driven proton pump in microorganisms |
| Keratin | Structural protein in hair, nails, and skin |
| Collagen | Structural protein in connective tissues |

### Hydrogen Bond Pattern

```text
Residue i      →      Residue i+4
     O  ------------------  N
        Hydrogen Bond
```

<img width="906" height="146" alt="image" src="https://github.com/user-attachments/assets/b72641a1-8b64-40d1-8ad5-3a3320b997c9" />


### Summary

The **alpha helix** is one of the most common protein secondary structures. It is stabilised by hydrogen bonds between amino acids four positions apart and plays an important role in the structure and function of many proteins.

---
## 6. Beta Strand and Beta Sheet

A **beta strand (β-strand)** is an extended segment of a protein chain. Multiple beta strands can align and interact through hydrogen bonds to form a **beta sheet (β-sheet)**.

### Key Features

- Stabilised by **hydrogen bonds between adjacent strands**
- Can involve **longer-range interactions** between distant regions of a protein sequence
- Beta sheets may be **parallel** or **antiparallel**
- Can fold into **curved sheets** or **beta barrels**
- Important for protein stability and structural support

### Beta Strand vs Beta Sheet

| Structure | Description |
|------------|-------------|
| Beta Strand | A single extended segment of a protein chain |
| Beta Sheet | Multiple beta strands connected by hydrogen bonds |

### Characteristics of Beta Sheets

| Feature | Description |
|----------|-------------|
| Shape | Extended and pleated |
| Stabilisation | Hydrogen bonds between strands |
| Types | Parallel and antiparallel |
| Interactions | Often between distant sequence regions |
| Structures Formed | Curved sheets and beta barrels |

### Examples

| Protein | Role |
|----------|------|
| Fibroin (Silk) | Structural protein providing strength and flexibility |
| Porin Membrane Proteins | Form channels in bacterial outer membranes |
| Amyloid Fibrils | Protein aggregates associated with several diseases |

### Simple Representation

<img width="921" height="616" alt="image" src="https://github.com/user-attachments/assets/0d61fcbd-6681-454d-b8d0-6696adff2953" />


### Summary

Beta strands are extended protein segments that associate through hydrogen bonds to form beta sheets. These structures are common in many proteins and contribute significantly to protein stability, folding, and function.

---

## 7. Random Coil

A **random coil** is a protein region that does not adopt a regular secondary structure such as an alpha helix or beta sheet.

### Key Features

- Lacks a repeating, ordered structure
- Highly flexible compared to helices and sheets
- Often found in loops and linker regions
- Can connect alpha helices and beta sheets
- Frequently involved in protein interactions and binding sites
- May become structured upon binding to other molecules

### Characteristics of Random Coils

| Feature | Description |
|----------|-------------|
| Structure | Irregular and flexible |
| Stability | Less stable than helices and sheets |
| Function | Connects structured regions and enables flexibility |
| Location | Loops, turns, linker regions, and protein surfaces |
| Secondary Structure Symbol | C (Coil) |

### Example Representation

```text
Alpha Helix      Random Coil      Beta Sheet
HHHHHHHHHHH       CCCCCCC        EEEEEEEE
```

### Proteins Containing Random Coil Regions

| Protein Type | Role of Random Coil |
|-------------|---------------------|
| Enzymes | Flexible active-site loops |
| Antibodies | Antigen-binding loops |
| Transcription Factors | DNA-binding flexibility |
| Signalling Proteins | Protein-protein interactions |

### Predicted Secondary Structure Example

```text
Sequence:
GHWIATRGQLIREAYEDYRHFSSECPFIP

Structure:
CEEEEECHHHHHHHHHHHCCCHHHCCCCC
```

In this example:

- **E** = Beta strand
- **H** = Alpha helix
- **C** = Random coil

The random coil regions occur at the beginning, middle, and end of the sequence where no regular secondary structure is predicted.

<img width="1346" height="904" alt="image" src="https://github.com/user-attachments/assets/2da67f3f-10f3-4dba-84d0-495d1c32dcab" />


### Summary

Random coils are flexible, irregular protein regions that lack the repeating patterns of alpha helices and beta sheets. They play important roles in connecting structured domains, enabling flexibility, and facilitating molecular interactions.

---
