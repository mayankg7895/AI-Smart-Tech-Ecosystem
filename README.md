# AI-Smart-Tech-Ecosystem
import time
import random

def ai_surgery_simulation():
    print("AI-पावर्ड सर्जरी शुरू...")
    latency = random.uniform(0.001, 0.01)
    time.sleep(latency)
    print(f"सर्जरी पूरी हुई! लेटेंसी: {latency:.4f} सेकंड")

for _ in range(3):
    ai_surgery_simulation()
