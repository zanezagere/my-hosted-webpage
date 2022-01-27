# my-hosted-webpage
class Transaction:
    def __init__(self, amount: float = 0, note: str = ''):
        self.amount = amount
        self.note = note
        self.timestamp = datetime.datetime.now()
