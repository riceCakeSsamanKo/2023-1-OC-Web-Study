# Git
git은 총 working directory, staging area, local repository로 구성이된다. 
그리고 이 셋은 모두 사용자의 컴퓨터 내부에 존재한다.

## add
working area에서 작업한 내용을 add하여 staging area에 올린다. staging area에서는 작업중 변경된 내용이 저장된다.

## commit
staging area에서 commit하면 해당 내용들이 local repository에 올라간다.

## push
커밋한 내용들을 push하면 이를 깃허브와 같은 원격 레포지토리에 올려 서버에 저장할 수 있다.

## fetch
fetch를 통해서 원격 레포지토리에서의 변경사항을 확인 가능하다. fetch는 변경사항을 확인만 할 뿐 변경사항을 로컬 레포지토리로 가져오진 않는다.

## pull
원격 레포지토리를 clone하여 로컬 디렉토리로 가져오면 서버에 저장되어 있는 코드(변경사항)를 pull하여서 내 컴퓨터로 가져올 수 있다.