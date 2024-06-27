Overview

  1.Hand gesture recognition has attracted the attention of many researchers due to its wide applications in robotics, games, virtual reality, sign language and human-computer interaction. 

  2.Sign language is a structured form of hand gestures and the most effective communication way among hear-impaired people.

  3.Developing an efficient sign language recognition system to recognize dynamic isolated gestures encounters three major challenges, namely, hand segmentation, hand shape feature representation and gesture sequence recognition.


Algorithm Used 

  Deep Learning:
    
   Deep learning is a subset of machine learning that uses multilayered neural networks, called deep neural networks, to simulate the complex decision-making power of the human brain.
    
  CNN-Deep Learning:

   A Convolutional Neural Network (CNN) is a type of deep learning algorithm that is particularly well-suited for image recognition and processing tasks. It is made up of multiple layers, including convolutional   
   layers, pooling layers, and fully connected layers.
   
   ![imag 1_8299](https://github.com/Sriharikj/Sign-Language-Recognition-using-ten-hand-gesture-signs-/assets/110553288/25e530e4-1fa3-4d47-8137-81835079db85)

Implementation

  1.We’ll first use MediaPipe to recognize the hand and the hand key points. MediaPipe returns a total of 21 key points for each detected hand.

  2.These key points will be fed into a pre-trained gesture recognizer network to recognize the hand pose.

  0. WRIST                      15. RING_FINGER_DIP

  
  1. THUMB_CMC                                                                    
  
  2. THUMB_MCP
  
  3. THUMB_IP
  
  4. THUMB_TIP
  
  5. INDEX_FINGER_MCP
  
  6. INDEX_FINGER_PIP
  
  7. INDEX_FINGER_DIP
  
  8. INDEX_FINGER_TIP
  
  9. MIDDLE_FINGER_MCP
  
  10. MIDDLE_FINGER_PIP
  
  11. MIDDLE_FINGER_DIP
  
  12. MIDDLE_FINGER_TIP
  
  13. RING_FINGER_MCP

14. RING_FINGER_PIP



