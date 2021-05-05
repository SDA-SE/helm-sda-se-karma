# How to create a new release

(change ../sda-se-karma/Chart.yaml)

helm package ../sda-se-karma

helm repo index .

commit the changes and release a new tag