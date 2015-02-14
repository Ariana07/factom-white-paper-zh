# Factom_White_Paper_zh

《Factom白皮书》 中文协同翻译
=============================================

Factom公司近日发布一份白皮书，大致构思了一种概念型网络框架，这个新系统可以确保并提高留存在比特币Blockchain里的交易记录，文件及其他一些重要数据准确性。来自清华大学[toyhouse-xlp](http://toyhouse.cc)的同学们正在通过互联网的方式将其翻译成中文。

欢迎每一个人参与翻译和校对！

***

##一起来参与


### 参与步骤（页尾有详细的过程演示）
* fork主仓库
* 按照章节（页面）认领翻译(每次申请一个章节)，在下面这个`README.md`里找还没有被人申请的章节，写上（@你的github号），给主仓库的`master`分支提pull request；
* 提的pull request 被确认，合并到主仓库后，代表你申请的章节*占位*完成，开始翻译；
* 翻译过程请参 *翻译协作规范* ，完成翻译后提交pull request给主仓库的`master`分支；
* 校核完成后，从主仓库的`master`分支合并到主`publish`分支；
* 全部翻译完成后，生成PDF文档和网页发布；


### 翻译协作规范
为了让大家协作顺畅，需要每一个人遵循如下协作规范~

- 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
- 翻译后的文档请放到SOURCE文件夹下的对应章节中，然后pull request即可，我会用gitbook编译成网页
- 工作分支为`master`，用于GitHub的pages服务
- fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到`master`分支中
- 有其他任何问题都欢迎发issue，我们看到了会尽快回复


如果不熟悉的Markdown的，请参考

- https://help.github.com/articles/markdown-basics
- https://help.github.com/articles/github-flavored-markdown

***

## 认领章节记录

* [概述](README.md)
* [Abstract](abstract/README.md)
* [Design Goals](design_goals/README.md)
* [The Factom Ecosystem](the_factom_ecosystem/README.md)
* [Security and Proofs](security_and_proofs/README.md)
   * [How Factom Secures Entries](security_and_proofs/how_factom_secures_entries.md)
   * [How Factom Servers and Auditing Servers Validate Entries](security_and_proofs/how_factom_servers_and_auditing_servers_validate_entries.md)
   * [Proving a Negative](security_and_proofs/proving_a_negative.md)
   * [How Applications Validate Factom Chains](security_and_proofs/how_applications_validate_factom_chains.md)
   * [How Factom Federated Servers Manage Chains](security_and_proofs/how_factom_federated_servers_manage_chains.md)
* [Factom System Overview](factom_system_overview/README.md)
   * [Directory Layer: How the Directory Layer Organizes Merkle Roots](factom_system_overview/directory_layer_how_the_directory_layer_organizes_merkle_roots.md)
   * [Entry Block Layer: How the Entry Block Layer Organizes Hashes and Data](factom_system_overview/entry_block_layer_how_the_entry_block_layer_organizes_hashes_and_data.md)
   * [Entries: How Entries are Created](factom_system_overview/entries_how_entries_are_created.md)
   * [Chains: How Entries are Organized into Chains](factom_system_overview/chains_how_entries_are_organized_into_chains.md)
* [The Factom Peer-to-Peer Network](the_factom_peer-to-peer_network/README)
   * [Factom Peer-to-Peer Communications](the_factom_peer-to-peer_network/factom_peer-to-peer_communications.md)
   * [Data Preservation and Dissemination](the_factom_peer-to-peer_network/data_preservation_and_dissemination.md)
* [A Deeper Discussion of Factom](a_deeper_discussion_of_factom/README)
   * [How to Name Factom Chains](a_deeper_discussion_of_factom/how_to_name_factom_chains.md)
   * [Using Factoids to Purchase Entry Credits](a_deeper_discussion_of_factom/using_factoids_to_purchase_entry_credits.md)
   * [Using Entry Credits to Purchase Entries](a_deeper_discussion_of_factom/using_entry_credits_to_purchase_entries.md)
   * [Setting the Cost of Entries with a Central Server Oracle](a_deeper_discussion_of_factom/setting_the_cost_of_entries_with_a_central_server_oracle.md)
   * [Using Factom without Factoids](a_deeper_discussion_of_factom/using_factom_without_factoids.md)
   * [First Entries on Entry Chains: Support for Homesteading](a_deeper_discussion_of_factom/first_entries_on_entry_chains_support_for_homesteading.md)
* [Conclusion](conclusion/README)
* [Bibliography](bibliography/README)
* [Appendix 1](appendix_1/README.md)
   * [How to Create Useful Applications Today Using the Factom Protocol](appendix_1/how_to_create_useful_applications_today_using_the_factom_protocol.md)
* [Appendix 2](appendix_2/README.md)
   * [Denial of Service from Spam](appendix_2/denial_of_service_from_spam.md)
   * [Sybil Attack of the DHT](appendix_2/sybil_attack_of_the_dht.md)
   * [Man in the Middle](appendix_2/man_in_the_middle.md)
   * [Dictionary Attack](appendix_2/dictionary_attack.md)
   * [Denial of Chain](appendix_2/denial_of_chain.md)
   * [Fraudulent Servers](appendix_2/fraudulent_servers.md)
* [Appendix 3](appendix_3/README.md)
   * [How the Factom Timestamping Mechanism Secures Transactions in the Blockchain](appendix_3/how_the_factom_timestamping_mechanism_secures_transactions_in_the_blockchain.md)
* [Appendix 4](appendix_4/README.md)
   * [How Factom Differs from Bitcoin and Sidechains](appendix_4/how_factom_is_different_from_other_blockchain_technologies.md)
   * [How Factom is Different from Other Blockchain Technologies](appendix_4/how_factom_differs_from_bitcoin_and_sidechains.md)
* [Appendix 5](appendix_5/README.md)
   * [Factom Consensus Similarities and Differences from Proof of Stake](appendix_5/factom_consensus_similarities_and_differences_from_proof_of_stake.md)
   * [Stake Grinding](appendix_5/stake_grinding.md)


***
## 参与者
- [Ariana07](https://github.com/ariana07)

## 鸣谢
- Material Design 中文协同翻译
参照了协同翻译规则。

