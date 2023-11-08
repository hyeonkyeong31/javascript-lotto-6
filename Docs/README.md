Lotto 클래스의 메서드:

constructor: Lotto 인스턴스를 생성하고, 주어진 번호를 검증하여 할당합니다.
getNumbers: 로또 번호를 반환합니다.
static generateRandomLotto: 무작위로 로또 번호를 생성한 후 Lotto 인스턴스를 반환합니다.
checkWinningNumbers: 주어진 당첨 번호와 보너스 번호와 비교하여 당첨 결과를 반환합니다.

App 클래스의 메서드:

play: 전체 로또 게임을 실행하는 메서드로, 다른 메서드들을 조합하여 게임을 진행합니다.
inputPurchaseAmount: 구매 금액을 입력 받고 예외 처리를 수행합니다.
purchaseLottos: 구매 금액을 기반으로 로또를 생성합니다.
inputWinningNumbers: 당첨 번호를 입력 받고 예외 처리를 수행합니다.
inputBonusNumber: 보너스 번호를 입력 받고 예외 처리를 수행합니다.
checkResults: 구매한 로또들과 당첨 번호를 비교하여 당첨 결과를 계산합니다.
printResults: 당첨 결과를 출력합니다.
getPrize: 당첨 등수에 대한 상금을 반환합니다.
calculateTotalPrize: 당첨 결과에 따른 총 상금을 계산합니다.
calculateTotalRate: 총 수익률을 계산합니다.
