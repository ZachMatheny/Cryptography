# Cryptography - Labs & Projects
<html>
	<body>
		<h1>Caesar & Vigenere Ciphers
	</body>
			<h2>Overview</h2>
			<p>
			In my "Caesar & Vigenere Ciphers" project, I explored classical encryption techniques comprehensively, focusing on the Caesar Cipher and the Vigenère Cipher.
			Through self-directed study and hands-on implementation, I delved into the intricacies of these ciphers, discerning their underlying principles and practical applications.
			Initially, I elucidated the distinctions between the Caesar and Vigenère ciphers, highlighting their shared utilization of the Latin alphabet for encryption while emphasizing the nuanced differences in their encryption methodologies.
			Additionally, I undertook the challenge of decrypting messages encoded with the Vigenère Cipher, recognizing its heightened complexity compared to the Caesar Cipher due to the intricate alignment of encryption keys and message text.
			Drawing from historical contexts, I uncovered notable instances of the Vigenère Cipher's utilization by the Confederacy during the American Civil War and the Swiss during World War I, enriching my understanding of its real-world significance.
			Furthermore, I applied my knowledge in practical encryption tasks, successfully encoding messages such as "Attack at dawn" using the Vigenère Cipher with the key "defend." Deepening my grasp of cryptographic principles, I explored the strategic design elements embedded within the Vigenère Cipher,
			namely confusion, diffusion, and their pivotal role in ensuring robust encryption. Complementing theoretical exploration with practical implementation, I developed Python scripts for encryption and decryption tasks within the Caesar Cipher framework,
			showcasing my ability to translate cryptographic concepts into functional software tools. Through this project, I honed my skills in cryptographic techniques, historical analysis, and software development, contributing to a comprehensive understanding of encryption methodologies within cybersecurity.
			</p>
			<h2> Tools Used</h2>
				<p>
			In undertaking the project, I leveraged a blend of software tools and technologies to explore classical encryption techniques and their practical applications. Through a combination of Visual Studio, Notepad++, Python, command-line interface (CLI), research tools, and cryptographic libraries,
			I navigated the complexities of cryptographic algorithms, historical research, and software development, crafting a comprehensive understanding of encryption methodologies within the realm of cybersecurity.
				</p>
				<ul>
				<li><strong>Visual Studio:</strong>Visual Studio served as the primary integrated development environment (IDE) for crafting Python scripts tailored to encryption and decryption tasks within the Caesar Cipher framework. Its feature-rich environment facilitated code writing, editing, debugging, 
				and project management, enhancing productivity and workflow efficiency.</li>
				<li><strong>Notepad++:</strong>Complementing Visual Studio, Notepad++ provided an additional text editing platform for refining Python scripts and managing project-related files. With its lightweight nature and versatile text editing capabilities, Notepad++ offered a streamlined environment for quick edits,
				code reviews, and script revisions.</li>
				<li><strong>Python:</strong>Python served as the programming language of choice for implementing encryption and decryption algorithms within the project. Its simplicity, readability, and extensive library support made it well-suited for cryptographic tasks, enabling seamless development and execution of cryptographic scripts.</li>
				<li><strong>Command-Line Interface (CLI):</strong>The command-line interface (CLI) provided a direct means of executing Python scripts and running encryption or decryption tasks. Interacting with the CLI facilitated swift testing, debugging, and execution of cryptographic algorithms, streamlining the development process.</li>
				</ul>
</html>

<html>
	<body>
		<h1>SHA-1 & MD5</h1>
			<h2>Overview</h2>
				<p>
				In Lab 1, MD5 and SHA-1 hashing algorithms were explored to generate cryptographic hashes for last names and text strings. 
				The length disparity between MD5 (128 bits) and SHA-1 (160 bits) was noted, with MD5 producing 32-character hashes and SHA-1 yielding more extended outputs. 
				Changes to characters in the last name did not alter the MD5 hash length but resulted in distinct hash values. Additionally,
				the hashing of a lengthy text string illustrated that message length does not directly correlate with hash length, emphasizing the cryptographic properties of these algorithms.
				Lab 2 was a deep dive into the world of reverse MD5 lookup. I attempted to decipher the original message from a given MD5 hash (0BAEA2F0AE20150DB78F58CDDAC442A9). Through Google search, 
				I inferred that brute force techniques, rather than pre-computed tables, were possibly employed to deduce the original message, identified as 'superuser.' 
				This exercise underscored the vulnerability of weak hash functions to brute-force attacks and the critical importance of using robust cryptographic algorithms in cybersecurity practices.
				In Lab 3, an exploration of hash algorithms' outputs for a specific numerical value (1701) was conducted on an external webpage. While providing visual representations of hash outputs, 
				it was discerned that this page did not alter hash secrecy or integrity. Instead, it was an illustrative tool for understanding hash representations across different algorithms, 
				highlighting the diversity and complexity inherent in cryptographic hashing.
				Lastly, Lab 4 involved using MD4 hashing with Unicode encoding to generate a Windows hash for the word "Puppy." A Windows hash was successfully created by applying the prescribed script, 
				demonstrating the practical application of cryptographic hashing techniques in operating system security.
				These lab exercises contributed to an enhanced understanding of cryptographic hashing principles, hash length disparities, reverse hash lookup methodologies, and the practical implications of hash algorithm selection in cybersecurity contexts.
				</p>
			<h2>Tools Used</h2>
			<p>
			Embarking on a journey through the realm of cybersecurity, I've engaged with diverse tools, technologies, and projects to deepen my understanding and proficiency in safeguarding digital assets and mitigating security risks. 
			From cryptographic hashing algorithms to reverse hash lookup techniques, each tool and project has provided invaluable insights into the intricate landscape of cybersecurity, equipping me with the knowledge and skills necessary to navigate the complex challenges of the digital age.
			</p>
			<ul>
			<li><strong>MD5 and SHA-1 Hashing Algorithms:</strong>Explored the workings of MD5 (Message Digest Algorithm 5) and SHA-1 (Secure Hash Algorithm 1) hashing algorithms, widely used for generating cryptographic hashes of data. MD5 produces a 128-bit (32-character) hash while SHA-1 generates a 160-bit hash.
			These algorithms are fundamental to data integrity verification and authentication processes in cybersecurity.</li>
			<li><strong>Google Search for Reverse MD5 Lookup:</strong>Utilized Google search for reverse MD5 lookup, attempting to decipher original messages from hashed values. This exercise provided practical exposure to hash decryption methodologies and highlighted the importance of robust hashing algorithms in resisting brute force attacks.</li>
			<li><strong>External Webpage Exploration for Hash Outputs:</strong>Explored an external webpage showcasing hash outputs for specific numerical values across different algorithms. This exploration deepened understanding of hash functions' complexities and provided insights into various hash representations used in cryptographic applications.</li>
			<li><strong>MD4 Hashing with Unicode Encoding:</strong>Implemented MD4 hashing algorithm with Unicode encoding to create Windows hashes, contributing to the exploration of cryptographic hashing techniques. MD4 is an older hashing algorithm known for its vulnerability to collision attacks, highlighting the importance of using secure hash functions in cybersecurity practices.</li>
			<li><strong>Visual Studio and Notepad++:</strong>Leveraged Visual Studio and Notepad++ as integrated development environments (IDEs) and text editors for crafting and refining Python scripts and project-related files. These tools facilitated seamless development and execution of cryptographic scripts, enhancing workflow efficiency.</li>	
			<li><strong>Python Programming Language:</strong>Harnessed the power of Python programming language for implementing encryption and decryption algorithms. Python's simplicity and extensive library support made it well-suited for cryptographic tasks, enabling the development of robust and efficient cryptographic solutions.</li>	
			<li><strong>Command-Line Interface (CLI):</strong>Interacted with the command-line interface to execute cryptographic scripts, test algorithms, and debug code. This direct interaction streamlined the development process and facilitated efficient testing and validation of cryptographic implementations.</li>	
			<li><strong>Research Tools and Resources:</strong>Leveraged various research tools such as online databases, academic journals, and digital libraries to gather insights into cryptographic principles and real-world applications. These resources enriched the depth and breadth of cybersecurity knowledge, informing decision-making and problem-solving in cybersecurity endeavors.</li>				
			</ul>
			<p>
			This compilation of tools, technologies, and projects reflects a multifaceted exploration of cybersecurity domains, encompassing cryptographic fundamentals, hash function analysis, reverse engineering methodologies, and practical software development skills essential for addressing contemporary cybersecurity challenges.
			</p>
	</body>
</html>

<html>
	<body>
		<h1>SHA-256 & Blockchain</h1>
			<h2>Overview</h2>
				<p>
				Immersed in the dynamic cybersecurity landscape, this lab is a voyage of discovery into cryptographic principles, blockchain technology, and public-private key cryptography.
				It's a meticulously structured journey, divided into two parts, designed to deepen my understanding of cryptographic techniques and showcase my practical application in securing digital transactions and maintaining data integrity within blockchain networks.
				</p>
				<h3> Part 1: SHA-256, Hashes, & Blockchain</h3>
					<ol>
					<li><strong>SHA-256 Hashing:</strong>I calculated SHA-256 hashes, meticulously analyzing scenarios with varying text inputs and capitalization patterns. This exercise demonstrated SHA-256's cryptographic properties, captured through meticulously documented screenshots for comprehensive analysis.</li>
					<li><strong>Single Block Mining:</strong>Explored message signing and verification mechanisms using public-private key pairs, meticulously documenting message integrity verification outcomes. I simulated man-in-the-middle attacks, meticulously altering message contents to assess verification robustness and cryptographic resilience.</li>
					<li><strong>Blockchain Construction:</strong>I Constructed and analyzed blockchains through sequential block mining, meticulously documenting resulting hashes and nonces. I scrutinized differences in hash outputs between blocks with identical text inputs, shedding light on blockchain integrity principles and the crucial role of randomness in maintaining data immutability.</li>
					<li><strong>Distributed Blockchain:</strong>Extended exploration to distributed blockchain networks, simulating data modifications within a single peer to observe ripple effects across the network. I meticulously documented changes in hash values and nonce recalculations, unraveling the intricacies of peer synchronization and blockchain consensus mechanisms.</li>
					<li><strong>Tokens and Ledger Data:</strong>I conducted experiments with ledger data across multiple peers, meticulously analyzing the impact of data modifications within individual peers on blockchain consistency and network-wide synchronization. This exercise provided me with invaluable insights into the intricate interplay between data integrity, peer consensus, 
					and blockchain security, underscoring the significance of the research.</li>	
					</ol>
				<h3>Part 2: Public & Private Keys in Blockchain</h3>
					<ol>
					<li><strong>Public/Private Key Pairs:</strong>I calculated and verified public-private key pairs, meticulously documenting key generation processes and mathematical relationships between keys. This exercise deepened my understanding of asymmetric cryptography fundamentals and their application in securing digital transactions within blockchain networks.</li>
					<li><strong>Message Signing:</strong>Explored message signing and verification mechanisms using public-private key pairs, meticulously documenting message integrity verification outcomes. I simulated man-in-the-middle attacks, meticulously altering message contents to assess verification robustness and cryptographic resilience.</li>
					<li><strong>Transaction Signing:</strong>Analyzed transaction signing and verification processes within blockchain networks, meticulously manipulating transaction values to understand their impact on verification outcomes. I identified discrepancies between original and altered transaction values, meticulously documenting verification failures and their implications for blockchain security.</li>
					<li><strong>Blockchain Transactions:</strong>Engaged in blockchain transaction experimentation, meticulously documenting changes in transaction values and ensuing block mining processes. I scrutinized the dynamic nature of blockchain data, meticulously assessing transaction integrity and network consensus mechanisms.</li>					
					</ol>
			<h2>Tools Used</h2>
				<p>
				This lab focused on the practical application of cryptographic principles and blockchain technology. I leveraged various tools and technologies to enhance my understanding and technical proficiency. Below is a list of the tools and technologies I used in this lab, as well as detailed technical descriptions.
				</p>
				<ul>
				<li><strong>SHA-256 Hash Algorithm:</strong>SHA-256 (Secure Hash Algorithm 256-bit) is a cryptographic hash function that generates a fixed-size 256-bit hash value from variable-length input data. It is part of the SHA-2 family and is widely used for data integrity verification and digital signatures in various security protocols.</li>
				<li><strong>Online Hashing Tools (Anders Brownworth's Blockchain Demo):</strong>These web-based tools are not just for observation but for active participation. They provide interactive demonstrations of cryptographic concepts and blockchain mechanics, allowing users to experiment with hashing, block mining, and blockchain construction.
				This hands-on approach offers a deeper understanding of these technologies.</li>
				<li><strong>Nonce:</strong>A nonce (number used once) is a random or pseudo-random number issued in cryptographic communication to ensure that old communications cannot be reused in replay attacks. In blockchain mining, the nonce is adjusted to find a hash that meets the network's difficulty requirement.</li>
				<li><strong>Block Mining:</strong>Block mining is validating and adding transactions to a blockchain by solving complex cryptographic puzzles. Miners compete to find a nonce that produces a hash with a specified number of leading zeros, ensuring the integrity and security of the blockchain.</li>
				<li><strong>Blockchain:</strong>A decentralized digital ledger that records transactions across multiple computers, ensuring paramount data integrity and security. Each block contains a list of transactions, a timestamp, and a reference to the previous block's hash, creating a chain of blocks. This robust structure is the backbone of blockchain technology, 
				emphasizing the importance of data integrity and security.</li>
				<li><strong>Distributed Blockchain Networks:</strong>These networks consist of multiple nodes (peers) that share and maintain a synchronized copy of the blockchain. Changes made by one peer must be validated and propagated across the network, ensuring consensus and preventing data tampering.</li>
				<li><strong>Public/Private Key Cryptography:</strong>This asymmetric encryption technique uses a pair of keys: a public key, which can be shared openly, and a private key, which remains confidential. It is used for secure data transmission, digital signatures, and blockchain transactions, ensuring data authenticity and integrity.</li>
				<li><strong>Message Signing and Verification:</strong>This process involves creating a digital signature using a private key and verifying the signature using the corresponding public key. It ensures the message has not been altered and confirms the sender's identity, crucial in secure communications and blockchain transactions.</li>
				<li><strong>Web-Based Blockchain Tools for Public/Private Keys:</strong>These tools facilitate generating, managing, and using public/private key pairs for various cryptographic operations. They allow users to sign messages, verify signatures, and perform secure transactions within blockchain environments.</li>
				<li><strong>Transaction Verification:</strong>This process involves confirming the authenticity and accuracy of transactions in a blockchain. It includes checking digital signatures, validating transaction amounts, and ensuring the transaction complies with the blockchain protocol, preventing fraud and double-spending.</li>				
				<li><strong>Hexadecimal Representation:</strong>Hexadecimal (base-16) is a numeral system used in computing and digital systems to represent binary data in a more human-readable format. It is commonly used to display cryptographic hash values, public/private keys, and binary data.</li>
				</ul>
				<p>
				Using these tools and technologies, I gained a comprehensive and technical understanding of cryptographic hashing, blockchain mechanics, public/private key cryptography, and secure transaction verification, enhancing my proficiency in cybersecurity practices.
				</P>
	</body>
</html>
