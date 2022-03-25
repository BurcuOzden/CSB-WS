# Complex modeling using ColabFold

This page is prepared to model the complex of phage G3P and E. Coli TolA coreceptor using ColabFold.
![image](https://user-images.githubusercontent.com/64282221/160189666-8a35114b-c9e9-49c0-9ace-aeeef34b1fe2.png)

## Biological Investigation:
- **Monomer 1:** Attachment protein G3P, Escherichia phage If1 (Bacteriophage If1)

Uniprot ID: O80297 https://www.uniprot.org/uniprot/O80297 

- **Monomer 2:** Cell envelope integrity inner membrane protein TolA, E. Coli

Uniprot ID: Q8X965 https://www.uniprot.org/uniprot/Q8X965 

![image](https://user-images.githubusercontent.com/64282221/160192504-4f68bf1b-e5d6-4091-b0bc-a472bbd3f584.png)


## ColabFold
Website Link: https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb 

![image](https://user-images.githubusercontent.com/64282221/160191598-fb622958-7d70-4f60-8875-625fe5c134c9.png)


## Preparing input fasta files
- Input file should be provided as one line.
- There should be **:** sign between sequences.
![image](https://user-images.githubusercontent.com/64282221/160192010-32c239a1-1e46-47f7-8373-2f12d4851442.png)

- **Final input sequence in ColabFold format:**
MKKIIIALFFAPFFTHATTDAECLSKPAFDGTLSNVWKEGDSRYANFENCIYELSGIGIGYDNDTSCNGHWTPVRAADGSGNGGDDNSSGGGSNGDSGNNSTPDTVTPGQTVNLPSDLSTLSIPANVVKSDSIGSQFSLYTNASCTMCSGYYLSNNADSIAIANITETVKADYNQPDMWFEQTDSDGNHVKILQNSYKAVSYNVESKQSDVNNPTYINYSYSVNVKQVSYDTSNVCIMNWETFQNKCDASRAVLITDTVTPSYSRNITIQSNINYQGSNGSGGSGGSGGSGNDGGGTGNNGNGTGDFDYVKMANANKDALTESFDLSALQADTGASLDGSVQGTLDSLSGFSDSIGGLVGNGSAISGEFAGSSAAMNAIGEGDKSPLLDSLSFLKDGLFPALPEFKQCTPFVFAPGKEYEFIIECKYIDMFKGIFAFILYFWTFVTVYDSFSGILRKGRG:MSKATEQNDKLKRAIIISAVLHVILFAALIWSSFDENIEASAGGGGGSSIDAVMVDSGAVVEQYKRMQSQESSAKRSDEQRKMKEQQAAEELREKQAAEQERLKQLEKERLAAQEQKKQAEEAAKQAELKQKQAEEAAAKAAADAKAKAEADDKAAEEAAKKAAADAKKKAEAEAAKAAAEAQKKAEAAAAALKKKAEAAEAAAAEARKKAAAEKAAADKKAAEKAAAEKAAADKKAAAEKAAADKKAAAAKAAAEKAAAAKAAAEADDIFGELSSGKNAPKTGGGAKGNNASPAGSGNTKNNGASGADINNYAGQIKSAIESKFYDASSYAGKTCTLRIKLAPDGMLLDIKPEGGDPALCQAALAAAKLAKIPKPPSQAVYEVFKNAPLDFK

- Please copy and paste the above file to the **_query_sequence_** section and please run all.
![image](https://user-images.githubusercontent.com/64282221/160193033-37a8a55f-904a-4cf0-b43b-db9525f004fe.png)
