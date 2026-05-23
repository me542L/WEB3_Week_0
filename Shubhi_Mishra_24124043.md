# Problem 1: Explaining Consensus

Imagine a game is being played using gold coins. A gives B 5 coins, B gives C 2 coins, and C gives D 1 coin. After some time everyone may forget who gave what, or someone can try to cheat by saying, “I never received those coins,” or “I still have all my coins.” To avoid confusion, all the transactions are written down carefully in a notebook. The notebook keeps a complete record of who gave coins to whom, making the game fair and organized.

Now imagine this notebook is not a normal paper notebook but a digital notebook on the internet. Instead of being kept by just one person thousands of computers around the world keep their own copies of it. Whenever a new transaction happens, all the computers update their copies.

That shared digital notebook is called a blockchain.

The special thing about the notebook you and your friends were playing with is that there is no teacher, principal, or boss controlling the notebook. Similarly, for the huge digital notebook (blockchain), there is no central authority controlling or maintaining it. So what if someone tries to add fake transactions and cheat? How do all the computers agree on what should be written in it?

That agreement process is called **consensus**.

Consensus means that before a new transaction or block is added to the blockchain, many computers check whether it is correct. If most of them agree that the transaction is real and follows the rules, it gets added to the blockchain. If someone tries to cheat, the other computers reject it.

There are two popular ways to achieve consensus:

## Proof of Work

Suppose your class teacher gives a tough math puzzle and says whoever solves it first will get a chance to write the next line on the blackboard or add the next sticker to the class wall. Since solving the puzzle is really hard and the competition is tough too, nobody can easily cheat and win again and again.

In Proof of Work, computers compete by solving a very hard puzzle. The puzzle is not impossible but it takes lots of guessing and computer power. The first computer to solve the puzzle wins the chance to add the next block of transactions to the blockchain.

Then al the other computers quickly check the answer. If it is correct everyone accepts the new block. As a reward the winner gets some digital coins.

But there is one problem which is thousands of computers work very hard all the time, which uses a lot of electricity. That is why another method was introduced.

## Proof of Stake

Suppose the class teacher plays another game where children put some candies into a safety box before playing. If someone follows the rules, they may win extra candies. But if they cheat, their candies are taken away. Because nobody wants to lose their candies, all the students try to stay honest.

Proof of Stake works in a very similar way.

In Proof of Stake, instead of using powerful computers to solve puzzles people earn the right to update the notebook by showing they have something valuable at risk. This is called **staking**.

The blockchain then chooses one of these people, called **validators**, to add the next block. Usually, people with more stake have a higher chance of being selected but the selection is often random to sime extent.

The chosen validator checks transactions and creates the next block. Other validators then check it as well. If most agree it is correct the block is added to the blockchain.

Honest validators earn rewards, while dishonest ones can lose some of their staked coins. This punishment is called **slashing**.

The whole idea of consensus is about building trust between thousands of strangers on the internet. Since nobody personally knows everyone else online, blockchain creates special rules so that thousands of computers can work together, agree on what is true, and automatically prevent cheating.

# Problem 2

When I changed the data in Block 2 the hash value of that block changed immediately because the hash depends on the data stored inside that block. Since Block 3 cpntains the hash of Block 2 as previous hash, the link between them no longer matched, so Block 3 became invalid. After that the same problem spreads to Block 4 and Block 5 (to all the remaining blocks after Block 2 in the blockchain) because each block is connected to the one before it through hashses. This created a ripple effect where all the blocks after Block 2 were affected because of changes made in Block 2. This happens because blockchain is designed so that every block is securely linked to the previous block, making it very difficult to change information without affecting the entire chain
