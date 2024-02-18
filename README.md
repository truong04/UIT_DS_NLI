# UIT_DS_NLI
Source pipeline code thi bảng B task Natural Language Interference
nhóm tụi mình đã tách task NLI ra thành 2 phần là evidence retrieval và classification. input sẽ là 1 đoạn văn bản và 1 câu Premise đưa vaò evidence retrieval sẽ trả lại cho chúng ta 1 cặp Premise và hypothesis rồi sau đó đưa cặp này vào phần classification để phân loại label

với evidence retrieval thì chúng mình dựa vào ensemble kết hợp nhiều pretrained model nhưng không tiến hành việc transfer learning

với classification tụi mình dùng pretrained model là xlm-roberta và tiến hành transfer learning trên đó để phân loại
